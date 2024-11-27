# Doge Alerts

**Doge Alerts** is a decentralized, transparent community alert website where anyone can contribute via GitHub to maintain and update all alerts related to the Dogecoin ecosystem. Whether it's blockchain issues, wallet problems, or scams, **Doge Alerts** provides a platform for the community to stay informed.

## How to Use

To get started, follow these steps:

### 1. Install GitHub
If you don’t have GitHub installed, you can download it from [GitHub's official website](https://github.com/).

### 2. Clone the Repository

Clone the repository to your local machine using the following command:
```bash
git clone https://github.com/qlpqlp/DogeAlerts.git
```
## Set Up the Folder Structure

Inside the cloned repository, you'll need to set up the `alerts` folder with specific subfolders. If the `alerts` folder doesn't already exist, create it manually.

You should create the following folders:

- `blockchain` – Everything related to the Dogecoin blockchain.
- `community` – Everything related to Dogecoin community events, news, or notifications.
- `exchange` – Anything related to Dogecoin on an exchange.
- `scam` – All scams related to Dogecoin, such as tokens using the name "Doge" to deceive the community.
- `wallet` – Everything related to Dogecoin wallets.

Each of these main folders can have two subfolders for status:

- `active` – Posts that are still active, recent, or not yet concluded.
- `closed` – Posts that no longer need to be listed as active.

---

## Creating Alert Posts

For each alert, create a `.txt` file inside the appropriate folder (either under `active` or `closed`). The filename should be the Date and Time of the Alert with the format `YYYY-MM-DD_HH-MM-SS.txt` example `2024-11-27_16-20-00.txt`, and the first line inside the `.txt` file should be the **full URL** of the source of the alert and the second line should be the **Title** of the alert.

### Example:
- **File Name**: 
`2024-11-27_16-20-00.txt`

- **File Content**: 
`https://dogechain.info/wallet/
Dogechain.info wallet shutdown`

---

## Create a Pull Request

Once you've added or updated the alerts, push your changes to your GitHub fork and create a pull request (PR) to the `main` branch of the original repository (`qlpqlp/DogeAlerts`). This PR will be reviewed by the community, and once approved and merged, it will become available to everyone on [DogeAlerts.com](https://dogealerts.com).

---

By contributing, you're helping keep the Dogecoin community informed and safe. Thank you for being a part of the Doge Alerts ecosystem!

If you have any questions or suggestions, feel free to open an issue in the [GitHub repository](https://github.com/qlpqlp/DogeAlerts/issues).

Just copy this content and paste it into your `README.md` file. It provides all the necessary information for contributors on how to set up the repository, structure their contributions, and create pull requests for the Doge Alerts project.


