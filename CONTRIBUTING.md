# Contributing to Lascaux Node Directory

Thank you for your interest in contributing to the Lascaux node directory! This guide outlines the process and requirements for submitting your node and ensuring smooth collaboration.

---

## How to Contribute

### 1. **Fork and Clone the Repository**
To get started, fork this repository and clone it to your local machine.

```bash
# Fork the repository via GitHub, then clone your fork locally
git clone https://github.com/your-username/lascaux-nodes.git
cd lascaux-nodes
```

### 2. **Add Your Node**
Edit the `nodes.json` file and add your node’s information in the required format:

```json
{
    "nodeURL": "https://your-node-domain.com",
    "nodeName": "Your Node Name",
    "nodeImg": "https://your-node-domain.com/logo.png",
    "nodeWallet": "YourTLSWalletAddress",
    "nodeDescription": "A brief description of your node."
}
```

Ensure that:
- **`nodeImg`**: The image is hosted at your node’s domain and meets community standards.
- **`nodeWallet`**: The wallet address is accurate, as it may be used for future rewards.
- **`status`**: Currently, only public nodes are supported. Mark your node as `"public"`.

### 3. **Test Your JSON**
Validate your JSON for proper formatting to avoid issues during the pull request process.

### 4. **Commit Your Changes**
Once you’ve added your node, stage your changes and commit them with a meaningful message:

```bash
git add nodes.json
git commit -m "Add [Your Node Name] to Lascaux node directory"
```

### 5. **Push Changes to Your Fork**
Push your changes to the `main` branch of your fork:

```bash
git push origin main
```

### 6. **Submit a Pull Request**
Go to the original Lascaux node repository and submit a pull request (PR) from your fork. Include details about your node and why it should be added.

---

## Contribution Guidelines

### Node Information Requirements
- **Valid Node URL**: Your `nodeURL` must point to an operational Lascaux backend with SSL enabled.
- **Node Image**: The `nodeImg` must be a valid URL pointing to a representative image hosted on your domain. Explicit or inappropriate images will not be accepted.
- **Node Wallet**: The `nodeWallet` should be a Telestai wallet address. It may be used for tracking activity and distributing future rewards.
- **Node Description**: Keep the description concise and relevant.

### Review Process
- PRs will be reviewed for accuracy, adherence to guidelines, and functionality of the provided node URL.
- Allow up to 72 hours for the review process.

---

## Best Practices

1. **Keep Your Node Online**: Nodes must remain operational to stay listed. We do understand that sometimes nodes go offline, and brief outages are fine.
2. **Maintain Data Integrity**: Ensure your node provides consistent and reliable data to the Lascaux platform.
3. **Follow Community Standards**: Adhere to all Lascaux and Telestai community guidelines.

---

## FAQs

**Q: Can I list a private node?**  
A: Private nodes are not currently supported, yet.

**Q: What happens if my node goes offline?**  
A: Offline nodes may be removed from the directory until they are restored.

**Q: Can I update my node information?**  
A: Yes, you can submit a PR to update your node details at any time.

---

## Need Help?

If you encounter any issues or have questions, feel free to reach out on the [Telestai Discord](https://discord.gg/VmFXfHnZE5). Our community is here to help!

Thank you for contributing to the Lascaux node ecosystem!