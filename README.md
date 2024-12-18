# Lascaux Node Directory

Welcome to the official Lascaux node directory! This repository allows community members to submit their nodes to be displayed on the Lascaux platform. Node operators can make pull requests (PRs) to add their node information.

---

## Node Information Requirements

Each node entry in the `nodes.json` file must include the following fields:

- **`nodeURL`**: The URL where the node is hosted (e.g., `https://testnetv1.telestai.io`) and reachable by the public.
- **`nodeName`**: A unique, user-friendly name for the node (e.g., `Frog World`).
- **`nodeImg`**: A URL pointing to the node’s logo or representative image.
  - The image must be hosted at the node’s URL.
  - Ensure the image is appropriate and aligns with community standards. The node will be displayed on the Lascaux platform and subject to removal if it does not align with community standards.
- **`nodeWallet`**: The Telestai wallet address associated with the node. **This may be used for future rewards!**
- **`nodeDescription`** (Optional): A short description of the node’s purpose or the community behind it.
---

## Example Node Entry

```json
{
    "nodeURL": "https://example-node.telestai.io",
    "nodeName": "Frog World",
    "nodeImg": "https://example-node.telestai.io/logo.png",
    "nodeWallet": "TesExampleLQsowvYEYPXpSHkkapoTbVV7Xex",
    "nodeDescription": "Welcome to the swamp!"
}
```

---

## How to Submit Your Node

1. **Fork this Repository**
   - Click the "Fork" button on the top-right corner of this page to create your copy of this repository.

2. **Clone Your Fork**
   ```bash
   git clone https://github.com/your-username/lascaux-nodes.git
   cd lascaux-nodes
   ```

3. **Add Your Node**
   - Edit the `nodes.json` file and add your node’s information following the example above.

4. **Commit Your Changes**
   ```bash
   git add nodes.json
   git commit -m "Add [Your Node Name] to Lascaux node directory"
   git push origin main
   ```

5. **Submit a Pull Request**
   - Go to the original repository and create a PR with your changes.

---

## Rules and Guidelines

- **Node Image**: 
  - The `nodeImg` URL must point to a valid image hosted at your node’s domain.
  - Ensure the image adheres to community guidelines (e.g., no explicit content).
- **Node Requirements**: 
  - The node must be running the Lascaux backend with a valid SSL certificate.
  - Nodes must remain online and functional to stay listed.
- **Review Process**: 
  - PRs will be reviewed for accuracy and compliance. Please be patient.

---

## Questions or Support

For any questions, please reach out on the [Telestai Discord](https://discord.gg/VmFXfHnZE5).

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for more information on how to contribute to this project.
