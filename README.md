# north-american-octo-nemes
nemesis
<?xml version="1.0"?>
<doc>
    <assembly>
        <name>Newtonsoft.Json</name>
    </assembly>
    <members>
        <member name="T:Newtonsoft.Json.Bson.BsonObjectId">
            <summary>
            Represents a BSON Oid (object id).
            </summary>
        </member>
        <member name="M:Newtonsoft.Json.Bson.BsonObjectId.#ctor(System.Byte[])">
            <summary>
            Initializes a new instance of the <see cref="T:Newtonsoft.Json.Bson.BsonObjectId"/> class.
            </summary>
            <param name="value">The Oid value.</param>
        </member>
        <member name="P:Newtonsoft.Json.Bson.BsonObjectId.Value">
            <summary>
            Gets or sets the value of the Oid.
            </summary>
            <value>The value of the Oid.</value>
        </member>
        <member name="T:Newtonsoft.Json.Bson.BsonReader">
            <summary>
            Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.
            </summary>
        </member>
        <member name="T:Newtonsoft.Json.JsonReader">
            <summary>
            Represents a reader that provides fast, non-cached, forward-only access to serialized JSON data.
            </summary>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.#ctor">
            <summary>
            Initializes a new instance of the <see cref="T:Newtonsoft.Json.JsonReader"/> class with the specified <see cref="T:System.IO.TextReader"/>.
            </summary>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.Read">
            <summary>
            Reads the next JSON token from the stream.
            </summary>
            <returns>true if the next token was read successfully; false if there are no more tokens to read.</returns>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.ReadAsInt32">
            <summary>
            Reads the next JSON token from the stream as a <see cref="T:System.Nullable`1"/>.
            </summary>
            <returns>A <see cref="T:System.Nullable`1"/>. This method will return <c>null</c> at the end of an array.</returns>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.ReadAsString">
            <summary>
            Reads the next JSON token from the stream as a <see cref="T:System.String"/>.
            </summary>
            <returns>A <see cref="T:System.String"/>. This method will return <c>null</c> at the end of an array.</returns>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.ReadAsBytes">
            <summary>
            Reads the next JSON token from the stream as a <see cref="T:System.Byte"/>[].
            </summary>
            <returns>A <see cref="T:System.Byte"/>[] or a null reference if the next JSON token is null. This method will return <c>null</c> at the end of an array.</returns>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.ReadAsDecimal">
            <summary>
            Reads the next JSON token from the stream as a <see cref="T:System.Nullable`1"/>.
            </summary>
            <returns>A <see cref="T:System.Nullable`1"/>. This method will return <c>null</c> at the end of an array.</returns>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.ReadAsDateTime">
            <summary>
            Reads the next JSON token from the stream as a <see cref="T:System.Nullable`1"/>.
            </summary>
            <returns>A <see cref="T:System.String"/>. This method will return <c>null</c> at the end of an array.</returns>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.Skip">
            <summary>
            Skips the children of the current token.
            </summary>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.SetToken(Newtonsoft.Json.JsonToken)">
            <summary>
            Sets the current token.
            </summary>
            <param name="newToken">The new token.</param>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.SetToken(Newtonsoft.Json.JsonToken,System.Object)">
            <summary>
            Sets the current token and value.
            </summary>
            <param name="newToken">The new token.</param>
            <param name="value">The value.</param>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.SetStateBasedOnCurrent">
            <summary>
            Sets the state based on current token type.
            </summary>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.System#IDisposable#Dispose">
            <summary>
            Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.
            </summary>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.Dispose(System.Boolean)">
            <summary>
            Releases unmanaged and - optionally - managed resources
            </summary>
            <param name="disposing"><c>true</c> to release both managed and unmanaged resources; <c>false</c> to release only unmanaged resources.</param>
        </member>
        <member name="M:Newtonsoft.Json.JsonReader.Close">
            <summary>
            Changes the <see cref="T:Newtonsoft.Json.JsonReader.State"/> to Closed. 
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.CurrentState">
            <summary>
            Gets the current reader state.
            </summary>
            <value>The current reader state.</value>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.CloseInput">
            <summary>
            Gets or sets a value indicating whether the underlying stream or
            <see cref="T:System.IO.TextReader"/> should be closed when the reader is closed.
            </summary>
            <value>
            true to close the underlying stream or <see cref="T:System.IO.TextReader"/> when
            the reader is closed; otherwise false. The default is true.
            </value>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.SupportMultipleContent">
            <summary>
            Gets or sets a value indicating whether multiple pieces of JSON content can
            be read from a continuous stream without erroring.
            </summary>
            <value>
            true to support reading multiple pieces of JSON content; otherwise false. The default is false.
            </value>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.QuoteChar">
            <summary>
            Gets the quotation mark character used to enclose the value of a string.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.DateTimeZoneHandling">
            <summary>
            Get or set how <see cref="T:System.DateTime"/> time zones are handling when reading JSON.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.DateParseHandling">
            <summary>
            Get or set how date formatted strings, e.g. "\/Date(1198908717056)\/" and "2012-03-21T05:40Z", are parsed when reading JSON.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.FloatParseHandling">
            <summary>
            Get or set how floating point numbers, e.g. 1.0 and 9.9, are parsed when reading JSON text.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.DateFormatString">
            <summary>
            Get or set how custom date formatted strings are parsed when reading JSON.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.MaxDepth">
            <summary>
            Gets or sets the maximum depth allowed when reading JSON. Reading past this depth will throw a <see cref="T:Newtonsoft.Json.JsonReaderException"/>.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.TokenType">
            <summary>
            Gets the type of the current JSON token. 
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.Value">
            <summary>
            Gets the text value of the current JSON token.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.ValueType">
            <summary>
            Gets The Common Language Runtime (CLR) type for the current JSON token.
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.Depth">
            <summary>
            Gets the depth of the current token in the JSON document.
            </summary>
            <value>The depth of the current token in the JSON document.</value>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.Path">
            <summary>
            Gets the path of the current JSON token. 
            </summary>
        </member>
        <member name="P:Newtonsoft.Json.JsonReader.Culture">
            <summary>
            Gets or sets the culture used when reading JSON. Defaults to <see cref="P:System.Globalization.CultureInfo.InvariantCulture"/>.
            </summary>
        </member>
        <member name="T:Newtonsoft.Json.JsonReader.State">
            <summary>
            Specifies the state of the reader.
            </summary>
        </member>
        <member name="F:Newtonsoft.Json.JsonReader.State.Start">
            <summary>
            The Read method has not been called.
            </summary>
        </member>
        <member name="F:Newtonsoft.Json.JsonReader.State.Complete">
            <summary>
            The end of the file has been reached successfully.
            </summary>
        </member>
        <member name="F:Newtonsoft.Json.JsonReader.State.Property">
            <summary>
            Reader is at a property.
            </summary>
        </member>
        <member name="F:Newtonsoft.Json.JsonReader.State.ObjectStart">

*** The rest of the content is truncated. ***
