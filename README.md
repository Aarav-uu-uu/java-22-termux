# Java 22 Installer for Termux

This project provides bash scripts to install and remove Java 22 in Termux using proot. The installer script sets up Java 22 in a Debian environment within Termux, while the remover script cleans up Java 22 and its configurations.

## Installation

### Prerequisites

- Termux installed on your device.
- An internet connection.

### Installation Steps

1. **Run the following command in Termux:**

   ```sh
   pkg install wget && pkg update && pkg up && wget https://github.com/Aarav-uu-uu/java-22-termux/releases/download/v1.0.0/java22-installer.sh && bash java22-installer.sh
## Removal

To remove Java 22 and revert Termux to its previous state, follow these steps:

1. **Run the following command in Termux:**

   ```sh
   pkg install wget && pkg update && pkg up && wget https://github.com/Aarav-uu-uu/java-22-termux/releases/download/v1.0.0/java22-remover.sh && bash java22-remover.sh
