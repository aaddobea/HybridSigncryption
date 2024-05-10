Subject: Formal Verification of the Proposed Signcryption Protocol using Verifpal Symbolic software

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
The inception of blockchain technology has triggered the deployment of public key methods to safeguard on-chain data. While most existing methods may be unsuitable for blockchain implementation, they further increase the network scalability due to the scheme’s complexity. Moreover, the storage of massive data on-chain also exacerbates the scalability issues. Therefore, in addressing such problems, this article proposes a lightweight hybrid signcryption scheme to secure patient medical data. To overcome storage limitations, the proposed method leverages decentralized offchain storage for managing vast medical data, thereby reducing the complexities associated with onchain execution. The off-chain mechanism generates a hash that links the off-chain data to on-chain storage. Subsequently, the patient encodes the encrypted data into a smart contract, which is verified by the doctor. A security analysis is performed with Verifpal to ensure the security strength of the proposed model. An in-depth experimental analysis is carried out to assess the computational and Communication outcomes and compare the suggested approach against other relevant methodologies. A decentralized off-chain experiment is conducted to evaluate the performance of signcrypted data on decentralized off-chain storage.

### Installing Verifpal
Follow the official documentation https://verifpal.com/software/ to install Verifpal. 

### Executing Verifpal protocols
After installation,  you execute the Verifipal Protocol using the command: ./verifpal verify <model_to_verify>

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
