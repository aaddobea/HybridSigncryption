Subject: Verifpal Analysis of the Proposed Signcryption Protocol

---

### Overview

This repository contains a comprehensive Verifpal analysis of the proposed signcryption protocol outlined in the associated paper. Verifpal, a powerful formal verification tool, was employed to assess the security properties of the protocol rigorously. The Verifpal software can be obtained from the official website: [Verifpal Website](https://verifpal.com).The suitable version can be downloaded and installed on your operating system.

### How to Use

To replicate and extend our analysis, follow these steps:

1. **Setting Up the Environment:**
   The provided Verifpal analysis was developed using Visual Studio on macOS. Ensure you have Visual Studio installed and configured on your system.

2. **Executing the Analysis:**
   Run the Verifpal scripts included in this repository using Visual Studio. These scripts are crafted in Verifpal to model and verify the proposed signcryption protocol.

### Repository Structure

- `src/`: Contains the Verifpal scripts used for the analysis.
- `docs/`: Documentation related to the Verifpal analysis, including findings and insights.

### Abstract:  
During the last few years, Implantable Medical Devices (IMDs) have evolved considerably. IMD manufacturers are now starting to rely on standard wireless technologies for connectivity. Moreover, there is an evolution towards open systems where the IMD can be remotely monitored or reconfigured through personal commercial-off-the-shelf devices such as smartphones or tablets. Nevertheless, a major problem that still remains unsolved today is the secure establishment of cryptographic keys between the IMD and such personal devices. Researchers have already proposed various solutions, most notably by relying on an additional external device. Unfortunately, these proposed approaches are either insecure, difficult to realise in practice, or are unsuitable for the latest generation of IMDs. Motivated by this, we present HAT, a secure and practical solution to provide \emph{fine-grained} and \emph{dynamic access control} for the next generation of IMDs, while offering full control and transparency to the patient. The main idea behind HAT is to shift the access control responsibilities from the IMD to an external device under the user’s control, such as a smartphone, acting as the IMD's Key Distribution Center. We show that HAT only introduces minimal energy and memory overhead and formally prove its security using Verifpal.

### How to Contribute

We welcome contributions if you identify potential improvements, vulnerabilities, or have suggestions for enhancing the Verifpal analysis. Please follow the standard GitHub workflow:

1. Fork this repository.
2. Create a new branch for your contributions.
3. Make your changes and commit them with clear, concise messages.
4. Create a pull request detailing your modifications.

### Disclaimer

This Verifpal analysis is a living document, subject to updates and refinements. We encourage the community to engage, share insights, and collectively strengthen the security analysis of the proposed signcryption protocol.

### License

This project is licensed under the [MIT License](LICENSE.md) - see the [LICENSE.md](LICENSE.md) file for details.

---

Feel free to customize this template based on your specific project details and preferences.
