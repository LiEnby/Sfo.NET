# Sfo.NET
Super Simple param.sfo parser in C# .NET Framework.

Usage:                 
```
  Dictionary<string,object> SfoKeys = Sfo.ReadSfo(File.OpenRead(@"param.sfo"));     
```
or
```
  Dictionary<string,object> SfoKeys = Sfo.ReadSfo(File.ReadAlLBytes(@"param.sfo"));  
```
Reading values: 
```
  UInt32 AttributeMinor = (UInt32)SfoKeys["ATTRIBUTE_MINOR"];           
  Byte[] AccountId = (Byte[])SfoKeys["ACCOUNT_ID"];           
  String TitleId = (String)SfoKeys["TITLE_ID"];              
```
