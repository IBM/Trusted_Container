# Trusted_Container
Provide a trusted platform for with Image Encryption capabilities with secure key delivery and management based in root of trust and host attestation, which will be a foundation for a NIST reference architecture.

# Get Involved!

We are using issues to organize threads of conversation since the effort takes place across a multitude of technologies. Create an issue with some of your thoughts/ideas for collaboration or if you have any questions/topics to discuss!

# Related links to code used in architecture

Hardware Attestation based Image Encryption/Decryption
- KeyWrapping Library: https://github.com/lumjjb/seclkeywrap
- CRI-O 1.16 build: https://github.com/lumjjb/cri-o/tree/1.16_encryption_sample_integration
- Skopeo build: https://github.com/lumjjb/skopeo/tree/sample_integration

ISecL k8s Integration
- ISeCL K8s controller: https://github.com/intel-secl/k8s-extensions/

MCM Policies
- Trusted Node Policy: https://github.com/lumjjb/trusted-node-policy-controller
- Trusted Container Image Registry Policy: https://github.com/ycao56/trusted-container-policy-controller
