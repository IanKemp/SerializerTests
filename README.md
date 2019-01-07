# SerializerTests
A .NET Serializer testing framework.

This test framework compares the most popular and fastest serializers for .NET which was the input for https://aloiskraus.wordpress.com/2017/04/23/the-definitive-serialization-performance-guide/

The project compiles to .NET Framework 4.7 and .NET Core 2.0 where you can check out the serialization performance in your favorite .NET runtime. The currently tested serializers are:

- [BinaryFormatter](https://docs.microsoft.com/en-us/dotnet/api/system.runtime.serialization.formatters.binary.binaryformatter)
- [Bois](https://github.com/salarcode/Bois)
- [DataContractSerializer](https://docs.microsoft.com/en-us/dotnet/api/system.runtime.serialization.datacontractserializer)
- [fastJSON](https://github.com/mgholam/fastJSON)
- [FlatBuffers](https://github.com/google/flatbuffers)
- [GroBuf](https://github.com/skbkontur/GroBuf)
- [Hyperion](https://github.com/akkadotnet/Hyperion) (fork of Wire)
- [Jil](https://github.com/kevin-montrose/Jil)
- [Json.NET](https://www.newtonsoft.com/json)
- [MessagePack for C#](https://github.com/neuecc/MessagePack-CSharp)
- [MessagePack for CLI](https://github.com/msgpack/msgpack-cli)
- [Protobuf.NET](https://github.com/mgravell/protobuf-net)
- [ServiceStack](https://github.com/ServiceStack/ServiceStack)
- [SlimSerializer](https://github.com/agnicore/nfx)
- [Wire](https://github.com/rogeralsing/Wire)
- [XmlSerializer](https://docs.microsoft.com/en-us/dotnet/api/system.xml.serialization.xmlserializer)
- [ZeroFormatter](https://github.com/neuecc/ZeroFormatter)

This test suite tries its best to be fair and vendor-neutral. More than one serializer claims to be the fastest, now you can verify if that is really the case. If I have forgot a great serializer (should be as fast or faster than Protobuf) please drop me a note and I will include it. 
