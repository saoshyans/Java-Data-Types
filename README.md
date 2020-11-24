/**
* #Java Integer Types :
* 
* Type  | Storage-Requirement |  Range
* -----	+ ------------------- + ---------------------------------------------------------
* int 	| 4 bytes             | -2,147,483,648 to 2,147,483,647                          |
* short | 2 bytes             | -32,768 to 32,767                                        |
* long  | 8 bytes             | -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807  |
* byte  | 1 byte              | -128 to 127                                              |
* /---------------------------------------------------------------------------------------
*
* @Methods for  converting Signed Integer data to Unsigned :
* Type | Class                    | Method                         
* ---- + ------------------------ + ----------------------------------------------
* int  | Byte,Short,Integer,Long  | compareUnsigned(int x , int y)                |
* int  | Byte,Short,Integer,Long  | divideUnsigned(int dividend , int divisor)    |
* int  | Byte,Short,Integer,Long  | parseUnsignedInt(String s , int radix)        |
* int  | Byte,Short,Integer,Long  | remainderUnsigned(int diviter , int divisor)  |
* long | Byte,Short,Integer,Long  | toUnsignedLong( int x)                        |
* str  | Byte,Short,Integer,Long  | toUnsignedString(int i , int radix)           |
* --------------------------------------------------------------------------------
*
* #Java Floating-Point Types:
* 
* Type  | Storage-Requirement | Range
* ----- + ------------------- + ----------------------------------------------------------
* float | 4 bytes             | -3.40282356E+38F to +3.40282356E+38F                      |
*       |                     | -3.40282356E-38F to +3.40282356E-38F                      |
* double| 8 bytes             | -1.79769313486231580E+308d to +1.79769313486231580E+308d  |
*       |                     | -1.79769313486231580E-308d to +1.79769313486231580E-308d  |
* ----------------------------------------------------------------------------------------
* 
* #Java char Types:
* 
* Escape-Sequence | Meaning          | Unicode-Value
* --------------- + ---------------- + ---------------
* \b              | Backspace        | \u0008         |
* \t              | Tab              | \u0009         |
* \n              | Linefeed         | \u000a         |
* \r              | Carriage return  | \u000d         |
* \"              | Double quote     | \u0022         |
* \'              | Single quote     | \u0027         |
* \\              | Backslash        | \u005c         |
* ----------------------------------------------------
*/
