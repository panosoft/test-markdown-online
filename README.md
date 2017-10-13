# Utils.Error

Error Types and Encoding/Decoding

<span style="font-size: 115%; font-family: 'Courier New'"><span style="font-weight: bold">type <span style="color: #1184CE;">ErrorType</span>   
&nbsp;&nbsp;&nbsp;&nbsp;= FatalError   
&nbsp;&nbsp;&nbsp;&nbsp;| NonFatalError   
&nbsp;&nbsp;&nbsp;&nbsp;| RetryableError </span></span>

**type ErrorType
&nbsp;&nbsp;&nbsp;&nbsp;= FatalError   
&nbsp;&nbsp;&nbsp;&nbsp;| NonFatalError   
&nbsp;&nbsp;&nbsp;&nbsp;| RetryableError**

### **type ErrorType**
```elm
type ErrorType
    = FatalError   
    | NonFatalError   
    | RetryableError
```
Error Types

---

**errorTypeEncoder : Utils.Error.ErrorType -> Json.Encode.Value**

### **errorTypeEncoder**
```elm
errorTypeEncoder : Utils.Error.ErrorType -> Json.Encode.Value
```
ErrorType encoder

---

<span style="font-size: 115%; font-family: 'Courier New'"><span style="font-weight: bold"><span style="color: #1184CE;">errorTypeDecoder</span> : Json.Decode.Decoder Utils.Error.ErrorType</span></span>

ErrorType decoder
