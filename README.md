# Custom Data Structures & Text Processing Engine (C++)

A modular C++ library implementing Abstract Data Types (ADTs) from scratch without relying on the Standard Template Library (STL) for core containers. Built to handle custom alphabets, dictionary mappings, prefix trees (Tries), and word/character occurrence analysis.

## 🚀 Key Features & Architecture

* **Custom Alphabet (`UndavAlphabet`)**: Supports dynamic mapping between characters and integer indices with configurable start/end offsets (e.g., Binary, DNA, Base64, ASCII).
* **Linked-List Dictionary (`UndavDictionary`)**: Key-value store featuring custom iterator implementation (`UndavIterator`) and manual memory lifecycle management.
* **Prefix Tree / Trie (`UndavTrie`)**: Efficient word storage and frequency lookup structure indexed dynamically by the radix of the assigned alphabet.
* **Occurrence Counter (`UndavOcurrenceCounter`)**: Parses text streams handling multiple delimiters (`space`, `\t`, `\n`) to count exact character and word frequencies.

## 🧪 Quality Assurance & Testing

The project includes dedicated unit test suites (`AlphabetTestSuite` and `OcurrenceCounterTestSuite`) validating:
* Radix calculation and bidirectional index-to-character translation.
* Duplicate character filtering during alphabet initialization.
* Edge cases in word parsing, special symbols, and out-of-alphabet characters.

## 🛠️ Tech Stack
* **Language:** C++ (Manual memory management with pointers and dynamic allocation)
* **Concepts:** Abstract Data Types (ADTs), Object-Oriented Design principles, Unit Testing, Git.
