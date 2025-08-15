📦  Packer-Unpacker

The  Packer-Unpacker is a Java-based command-line utility that allows users to combine multiple files into a single packed file and later extract them back to their original form.
It’s similar to basic file archiving tools but implemented purely in Java for learning purposes, demonstrating file I/O operations, exception handling, and object-oriented programming concepts.

🚀 Features

Pack Files: Combine multiple files from a directory into a single packed file.

Unpack Files: Extract all files from the packed file back to the original directory.

Metadata Handling: Stores file names and sizes in the packed file for accurate reconstruction.

Cross-Platform: Works on any OS with Java installed.

Error Handling: Detects and reports missing files, corrupted archives, or invalid formats.

🛠️ Technologies Used

Java (JDK 8 or later)

Core Java I/O (FileInputStream, FileOutputStream, BufferedReader, etc.)

Custom Classes for packing/unpacking logic


├── Packer_UnPacker/
│   ├── MarvellousPacker.java
│   ├── MarvellousUnpacker.java
│   └── <other helper classes>.java
│
├── program478.java/program468.java      # Main driver program

