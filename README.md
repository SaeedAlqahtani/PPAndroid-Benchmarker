# PPAndroid-Benchmarker
PPAndroid-Benchmarker is a system for evaluating the effectiveness of Privacy Protection Apps of the Android platform. This system allows to, dynamically or statically, benchmark privacy protection apps designed for Android platform. It is designed to be oblivious to details of mobile privacy protection systems, and can detect performance of combined mobile privacy protection apps in run time -- this is why we use the term 'systems' rather than 'apps'. It is effectively a system:
1) simulating user-configured privacy leakage activities of a wide range of selections.
2) capturing what leakage attempts were successful.
3) supporting a high level of automation for the whole benchmarking life-cycle.

Currently, PPAndroid-Benchmarker is more to be a framework which is partially implemented. Privacy protection apps that apply dynamic analysis can be benchmarked using our system. We will continue developing it to cover planned future directions. For instance, there are two components which are described on a conceptual level in our paper (Automatic Test Apps Generator & Reconfigurability Engine). The former will extend PPAndroid-Benchmarker to cover static analysis privacy protection tools, while the latter allows adding (or removing some unwanted features) more sources and sinks to provide reconfigurability and extension of supported features.4) providing a good user interface for testers to configure benchmarking tasks.


Soon, our work is going to be published and we will start feeding PPAndroid-Benchmarker here and its paper for more details.
