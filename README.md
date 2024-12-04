# 🌊 Oasis AI: Decentralized AI Compute and Inference Platform

Oasis is an innovative platform designed to revolutionize the landscape of AI compute and inference through decentralization. Our mission is to empower businesses and consumers by connecting them with a vast network of decentralized computing resources. Users can access a variety of AI tools, including large language models (LLMs) and image generation capabilities, all crafted for efficiency and ease of use.

The code intends to autoatically complete the "Generate images with the Oasis AI Discord Bot" activity...

[Learn more about Oasis AI](https://x.com/DefiAlchemistry/status/1853349833865863515)

---

## 🚀 Getting Started

Follow these steps to set up the Oasis AI Discord Interaction project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/Defi-Alchemist/OasisAI-Discord-Interaction.git
cd OasisAI-Discord-Interaction
```

### 2. Clone the Repository

```bash
npm install
```

### 3.Configure Your Environment

```plaintext
AUTH_TOKEN=<your_auth_key>
```

#### To Obtain Your Auth Key:

1. **Add the Oasis Discord bot** to your profile: [Add Bot](https://discord.com/oauth2/authorize?client_id=1238009056451498024)
2. **Go to your DMs** with the bot: [Direct Messages](https://discord.com/channels/@me/1302916090040422491)
3. **Open Developer Tools**: Press `F12` and navigate to the **Network** tab.
4. **Start an image generation request** and look for the "interaction" network.
5. **Click on it**, scroll down, and copy the `auth key`.

### 4. Add Prompts

In the `prompts.txt` file, add your prompts line by line. The more prompts you include, the better the results! You can use ChatGPT to help generate these prompts.

### 5. Run the Code

```bash
node index.js
```

### 6. Check Your Stats

Return to the Discord channel and type `/stats`. If you see your Discord interactions increasing, congratulations! It's working.

---

## ⚠️ Known Issues & Future Upgrades

- **Tracking Points Increase**: Currently, we haven't tested if overall credits increase. From the AI creations I did manually, it did not affect overall credits. They may be calculated later.
- **Real-Time Discord Chat Connection**: This feature will enhance human-like interaction. I plan to implement this as soon as possible.
- **Future Maintenance**: I cannot guarantee ongoing updates for this project. Please feel free to fork it and add more features!

---

## 📢 Important Notice

This project aims to assist Oasis AI during its early beta phase. I will delete or archive the project after the full consumer launch and the $OASIS TGE. If any entity is found using this for commercial purposes, I do not hold any responsibility!
