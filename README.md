# Sfo.NET
Super Simple param.sfo parser in C# .NET Framework.

Usage:                 
  Dictionary<string,object> SfoKeys = Sfo.ReadSfo(Stream or Byte\[]);           
  UInt32 AttributeMinor = (UInt32)SfoKeys\["ATTRIBUTE_MINOR"];           
  Byte\[] AccountId = (Byte\[])SfoKeys\["ACCOUNT_ID"];           
  String TitleId = (string)SfoKeys\["TITLE_ID"];              
