# DeepL.NET

![DeepL.NET Logo](https://github.com/lecode-official/deepl-dotnet/blob/master/documentation/images/banner.png "DeepL.NET Logo")

A .NET wrapper for the [DeepL](https://www.deepl.com/translator) translation service. DeepL is a commercial translation service based on deep learning. This wrapper only supports v2 of the API as v1 of the API has been deprecated for new DeepL API plans available from October 2018.

## Features

- .NET Core and .NET Framework compatible
- Completely asynchronous (using the async-await pattern)
- Covers the complete DeepL API surface area
- Translate text
- Translate text containing XML
- Translate documents (Word, PowerPoint, HTML, and raw text documents)

## Developing

If you want to develop the project further, please install the [.NET Core SDK](https://dotnet.microsoft.com/download) and, if necessary, [Git](https://git-scm.com/downloads). After that you are ready to clone the repository and build the project:

```bash
git clone https://github.com/lecode-official/deepl-dotnet.git
cd deepl-dotnet
dotnet build
```

## Contributing

If you'd like to contribute, there are multiple ways you can help out. If you find a bug or have a feature request, please feel free to open an issue on [GitHub](https://github.com/lecode-official/deepl-dotnet/issues). If you want to contribute code, please fork the repository and use a feature branch. Pull requests are always welcome. Before forking, please open an issue where you describe what you want to do. This helps to align your ideas with mine and may prevent you from doing work, that I am already planning on doing. If you have contributed to the project, please add yourself to the contributors list (CONTRIBUTORS.md). To help speed up the merging of your pull request, please comment and document your code extensively and try to emulate the coding style of the project.

## License

The code in this project is licensed under MIT license. For more information see the [license file](https://github.com/lecode-official/deepl-dotnet/blob/master/LICENSE).
