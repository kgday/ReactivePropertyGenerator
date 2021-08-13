# ReactivePropertyGenerator
C# Source generator for reactive properties from fields decorated with [ReactiveProp]

(Code addapted from the roslyn-sdk samples)
https://github.com/dotnet/roslyn-sdk/blob/main/samples/CSharp/SourceGenerators/SourceGeneratorSamples/AutoNotifyGenerator.cs

The plan is to be able to save oneself the trouble of typing the fields and then the properties with this.RaiseAndSetIfChanged.  Simply install the nuget package and then
type the fields decorated with [ReactiveProp].  The properties will be generated for you and you can use them as though you typed them yourself.  The property name can be added as 
a parameter or else the property will be derived from the field name.

But unable to get it to work as present getting errors such as "An instance of analyzer ReactivePropertyGenerator.ReactivePropGenerator cannot be created .. ..Could not load file 
or assembl7 'Microsoft.CodeAnalysis' .. I shall look into this at some point.

