<a name="punycode"></a>

## punycode : <code>object</code>
Contains methods to work with Punycode strings.

**Kind**: global namespace  

* [punycode](#punycode) : <code>object</code>
    * [.decode(input)](#punycode.decode) ⇒ <code>string</code>
    * [.encode(input)](#punycode.encode) ⇒ <code>string</code>
    * [.unicode(input)](#punycode.unicode) ⇒ <code>string</code>
    * [.ascii(input)](#punycode.ascii) ⇒ <code>string</code>

<a name="punycode.decode"></a>

### punycode.decode(input) ⇒ <code>string</code>
Converts a Punycode string of ASCII-only symbols to a string of Unicode symbols.

**Kind**: static method of [<code>punycode</code>](#punycode)  
**Returns**: <code>string</code> - The resulting string of Unicode symbols  

| Param | Type | Description |
| --- | --- | --- |
| input | <code>string</code> | The Punycode string of ASCII-only symbols |

<a name="punycode.encode"></a>

### punycode.encode(input) ⇒ <code>string</code>
Converts a string of Unicode symbols (e.g. a domain name label) to a

**Kind**: static method of [<code>punycode</code>](#punycode)  
**Returns**: <code>string</code> - The resulting Punycode string of ASCII-only symbols  

| Param | Type | Description |
| --- | --- | --- |
| input | <code>string</code> | The string of Unicode symbols |

<a name="punycode.unicode"></a>

### punycode.unicode(input) ⇒ <code>string</code>
Converts a Punycode string representing a domain name or an email address

**Kind**: static method of [<code>punycode</code>](#punycode)  
**Returns**: <code>string</code> - The Unicode representation of the given Punycode string  

| Param | Type | Description |
| --- | --- | --- |
| input | <code>string</code> | The Punycoded domain name or email address to convert to Unicode |

<a name="punycode.ascii"></a>

### punycode.ascii(input) ⇒ <code>string</code>
Converts a Unicode string representing a domain name or an email address to

**Kind**: static method of [<code>punycode</code>](#punycode)  
**Returns**: <code>string</code> - The Punycode representation of the given domain name or email address  

| Param | Type | Description |
| --- | --- | --- |
| input | <code>string</code> | The domain name or email address to convert, as a Unicode string |
