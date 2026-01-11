🔍 In-Memory Search Engine
A high-performance in-memory search engine built using C++, Python, and Streamlit, demonstrating real-world search engine fundamentals.

🚀 Overview
This project implements a fast and efficient search system where all documents and indexes are stored entirely in RAM.
The core logic is written in C++ for speed, exposed to Python via pybind11, and visualized using an interactive Streamlit UI.

✨ Features
⚡ Inverted Index for fast word-to-document lookup
📊 TF-IDF Ranking for relevance-based search results
🔎 Phrase Search for exact matching
🔀 Boolean Search (AND / OR / NOT)
💡 Real-time Autocomplete (Trie-like approach)
🧠 In-Memory Processing (no disk or database usage)
🖥️ Interactive Streamlit UI
🛠️ Tech Stack
C++ – Core search engine & performance
pybind11 – C++ to Python binding
Python – Application logic
Streamlit – Web UI
CMake – Build system
