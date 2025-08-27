# Voter-System-
🗳 Blockchain Voting System

A simple Blockchain-based Voting System built in Python.
Each vote is stored as a block in the blockchain, ensuring security, transparency, and immutability.

✨ Features

Each vote is stored as a block in the blockchain.

Uses SHA-256 hashing for integrity.

Prevents tampering — votes cannot be modified once cast.

Shows all votes stored in the chain.

Provides vote counts for each candidate.

Includes blockchain validation check.

📂 Project Structure
Blockchain-Voting-System/
│── voting_system.py   # Main program
│── README.md          # Documentation

⚙️ Installation

Clone this repository:

git clone https://github.com/your-username/Blockchain-Voting-System.git
cd Blockchain-Voting-System


Run the program:

python voting_system.py

🚀 Usage

Enter the number of voters.

For each voter, provide:

Voter ID (unique)

Candidate name

The system will:

Store the vote in the blockchain.

Display all blocks with their hash values.

Show voting results (vote counts).

Verify if the blockchain is valid.

▶️ Example Run
🗳 Welcome to Blockchain Voting System 🗳
Enter number of voters: 3

Enter Voter ID for Voter 1: V1
Enter candidate name: Alice
✅ Vote added successfully!

Enter Voter ID for Voter 2: V2
Enter candidate name: Bob
✅ Vote added successfully!

Enter Voter ID for Voter 3: V3
Enter candidate name: Alice
✅ Vote added successfully!

--- Voting Results ---
Alice: 2 votes
Bob: 1 votes

Blockchain valid? True

🛠 Technologies Used

Python 3

hashlib (for SHA-256 hashing)

time (for timestamps)

📌 Future Improvements

Prevent duplicate voter IDs (double voting).

Add FastAPI / Streamlit UI for better interaction.

Store blockchain data in a file/database.

Implement cryptographic digital signatures for voters.

⚠️ Disclaimer

This project is for educational purposes only.
It demonstrates how blockchain can be applied in voting systems, but it is not production-ready for real elections.