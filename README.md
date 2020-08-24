# Sfo.NET
Super Simple param.sfo parser in C# .NET Framework.

Usage: 
Dictionary<string,object> SfoKeys = Sfo.ReadSfo(Stream or Byte\[]);
string TitleId = (string)SfoKeys\["TITLE_ID"];
