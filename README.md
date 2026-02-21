# File-Compression-Analyzer
File Compression Analyzer is a data compression project that implements the Greedy approach using Huffman Coding to reduce file size efficiently. It performs frequency analysis, builds a Huffman tree, encodes data, and compares original and compressed sizes.
🔍 Project Overview

File Compression Analyzer is a data compression project that demonstrates how the Greedy algorithm is applied in the Huffman coding technique to reduce file size efficiently.

This project analyzes input text files, generates Huffman codes based on character frequencies, compresses the file, and compares the original and compressed sizes to evaluate compression performance.

🚀 Key Features

📊 Frequency analysis of characters in a file

🌳 Construction of Huffman Tree using Greedy approach

🧮 Generation of optimal prefix codes

📦 File compression

📈 Compression ratio calculation

📉 Size comparison (Original vs Compressed)

📑 Performance analysis report

🧠 Algorithms Used
1️⃣ Greedy Algorithm

The greedy strategy is used to repeatedly select two nodes with the smallest frequency while building the Huffman Tree.

2️⃣ Huffman Coding

Huffman Coding is a lossless data compression algorithm that assigns variable-length codes to characters based on their frequencies.

More frequent characters → Shorter codes

Less frequent characters → Longer codes

This ensures optimal compression.

🛠️ Technologies Used

Programming Language: (C++ / Java / Python – update as per your project)

Data Structures:

Priority Queue (Min Heap)

Binary Tree

Maps / Hash Tables

📂 How It Works

Read input file

Count frequency of each character

Build Min-Heap

Construct Huffman Tree

Generate binary codes

Encode file

Calculate compression statistics
