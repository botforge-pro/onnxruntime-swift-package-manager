# Swift Package Manager for ONNX Runtime

> [!NOTE]
> This is a mirror of `microsoft/onnxruntime-swift-package-manager`, which disappeared from GitHub in November 2026 together with the rest of the ONNX Runtime repositories. The history up to upstream tag 1.24.2 (commit `b7fb7f7`) is unchanged. On top of it, the only change is where the two binary targets are downloaded from: the [binaries-1.24.2](https://github.com/botforge-pro/onnxruntime-swift-package-manager/releases/tag/binaries-1.24.2) release here instead of `download.onnxruntime.ai`. The checksums in `Package.swift` are Microsoft's own, so SwiftPM refuses any archive that differs from the one Microsoft published.
>
> To use it, replace `https://github.com/microsoft/onnxruntime-swift-package-manager` with `https://github.com/botforge-pro/onnxruntime-swift-package-manager` and keep the version requirement.

A light-weight repository for providing [Swift Package Manager (SPM)](https://www.swift.org/package-manager/) support for [ONNXRuntime](https://github.com/microsoft/onnxruntime). The ONNX Runtime native package is included as a binary dependency of the SPM package.


SPM is the alternative to CocoaPods when desired platform to consume is mobile iOS.

## Note

The `objectivec/` directory is copied from the [ORT repo](https://github.com/microsoft/onnxruntime/tree/main/objectivec) and it's expected to match. It will be updated periodically/before release to merge new changes.

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
