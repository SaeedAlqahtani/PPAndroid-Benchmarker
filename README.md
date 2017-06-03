# PPAndroid-Benchmarker
PPAndroid-Benchmarker is a system for evaluating the effectiveness of Privacy Protection Apps of the Android platform. It is designed to be oblivious to details of mobile privacy protection systems, and can detect performance of combined mobile privacy protection apps in run time -- this is why we use the term 'systems' rather than 'apps'. It is effectively a system:
1) simulating user-configured privacy leakage activities of wide range of selections.
2) capturing what leakage attempts were successful.
3) supporting a high level of automation for the whole benchmarking life-cycle.
4) providing a good user interface for testers to configure benchmarking tasks.

Currently, PPAndroid-Benchmarker is more to be a framework which is partially implemented. It can be applied now on privacy protection apps that apply dynamic analysis. We will continue developing it to cover all possible sinks and sources of sensitive information. Moreover, there are two components whcih are described on a conceptual level in our paper (Automatic Test Apps Generator & Reconfigurability Engine). The former will extend PPAndroid-Benchmarker to cover static analysis privacy protection tools, while the latter allows adding (or removing some unwanted features) more sources and sinks to provide reconfigurability and extension of supported features.

For more informaiton, we will provide later a link to our paper here once published.
