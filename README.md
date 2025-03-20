Виконала самостійно Слобожан Софія РПЗ-23А
# Тема: “Команди Linux для архівування та стиснення даних. Робота з текстом”

# Мета роботи: 
Отримання практичних навиків роботи з командною оболонкою Bash.
Знайомство з базовими командами для архівування та стиснення даних.
Знайомство з базовими діями при роботі з текстом у терміналі.
 # Task 2. 
   
![image](https://github.com/user-attachments/assets/f20c89f4-e7c7-4593-99d1-f07ade90b5aa)


# Task 3.

# 1. Create a file with the .tar extension

To create an empty .tar archive file, use the following command:

  tar -cvf myarchive.tar /dev/null
    -c: Create a new archive.
    -v: Verbose output (shows the progress).
    -f: Specify the name of the archive.
# 2. Create a .tar file that contains multiple files and directories at once
To create a .tar archive that includes several files and directories, use the following command:

tar -cvf myarchive.tar file1.txt file2.txt directory1/
Replace file1.txt, file2.txt, and directory1/ with the actual names of the files and directories you want to include.

# 3. View the contents of the file
To view the contents of the myarchive.tar file, use the following command:

  tar -tvf myarchive.tar
    -t: List the contents of the archive.
    -v: Verbose output.
    -f: Specify the name of the archive.

# 4. Extract the contents of the tar file
To extract the contents of the myarchive.tar file, use the following command:

  tar -xvf myarchive.tar
    -x: Extract files from the archive.
    -v: Verbose output.
    -f: Specify the name of the archive.


# 5. Create a tar archive file compressed with bzip
To create a compressed .tar.bz2 archive using bzip, use the following command:


  tar -cjvf myarchive.tar.bz2 file1.txt file2.txt directory1/
    -c: Create a new archive.
    -j: Compress the archive using bzip2.
    -v: Verbose output.
    -f: Specify the name of the archive.

# 6. Extract the contents of the tar bzip file
To extract the contents of the myarchive.tar.bz2 file, use the following command:

  tar -xjvf myarchive.tar.bz2
    -x: Extract files from the archive.
    -j: Decompress the bzip2 archive.
    -v: Verbose output.
    -f: Specify the name of the archive.

# 7. Create a tar archive file compressed with gzip
To create a compressed .tar.gz archive using gzip, use the following command:

  tar -czvf myarchive.tar.gz file1.txt file2.txt directory1/
    -c: Create a new archive.
    -z: Compress the archive using gzip.
    -v: Verbose output.
    -f: Specify the name of the archive.

# 8. Extract the contents of the tar gzip file
To extract the contents of the myarchive.tar.gz file, use the following command:

  tar -xzvf myarchive.tar.gz
    -x: Extract files from the archive.
    -z: Decompress the gzip archive.
    -v: Verbose output.
    -f: Specify the name of the archive.

  #  TASK 4.
  ![image](https://github.com/user-attachments/assets/64041bc3-592a-428e-b42d-c7b669d0395b)

# TASK 5.

![image](https://github.com/user-attachments/assets/d14571fc-8458-4de1-bb04-3045a1ad3bd2)
![image](https://github.com/user-attachments/assets/f5a07198-6df9-49a9-930b-61476fcdc922)

### answers to questions

# 1. Comparative Characteristics of Compression and Archiving Processes
# Compression:
    Purpose: To reduce the size of files for saving disk space or decreasing data transfer         time.
    Methods: Uses algorithms that eliminate redundant data or apply mathematical models to         reduce the volume of information.
# Types:
    Lossy Compression: Loses some data (e.g., JPEG for images).
    Lossless Compression: Retains all data (e.g., PNG for images, ZIP for files).
# Archiving:
    Purpose: To combine multiple files and directories into a single file for easier storage         and transfer.
    Methods: Preserves directory structure and allows for the storage of metadata                     (permissions, creation dates).
            Examples: Formats like tar, zip, 7z.
# 2. Programs for Compression and Archiving in Linux
 #   gzip:
 
        Used for compressing individual files. Creates files with the .gz extension.
        
# bzip2:

A compression program that provides a better compression ratio than gzip but operates more slowly. Creates files with the .bz2 extension.

# xz:

Uses the LZMA algorithm for compression, offering a high compression ratio but with significant memory requirements. Creates files with the .xz extension.

# 7zip (p7zip):    

A powerful archiver that supports many formats, including .zip, .tar, .gz, .bz2, .xz, and .7z. Provides a high level of compression.

# 3. Comparison of Compression Algorithms Used in Linux
# gzip:

Speed: Fast compression and decompression speeds, making it suitable for quick tasks.
Efficiency: Moderate compression ratio; good for general use.

# bzip2:

Speed: Slower than gzip, especially during compression.
Efficiency: Higher compression ratio than gzip, making it suitable for reducing file sizes significantly.

# xz:

Speed: Slowest among the three, especially during compression.
Efficiency: Offers the highest compression ratio, ideal for situations where maximum space savings are required.
# 4. Software Tools for Compression and Archiving on Mobile Phones

# WinZip:

A popular app for compressing and decompressing files on mobile devices, supporting various formats like ZIP and RAR.
# RAR:

An app that allows users to create and extract RAR and ZIP files, providing a user-friendly interface for managing archives.

# ZArchiver:

A free app for Android that supports a wide range of archive formats, including ZIP, RAR, and 7z, allowing users to create and extract archives easily.
iZip:

An app for iOS that enables users to create and manage ZIP files, providing features for viewing and extracting files from archives.
###Conclusion
During the completion of these tasks, the fundamental methods of archiving and compressing data in Linux were explored, specifically the use of the tar command for creating, viewing, and extracting archives. Different compression formats, such as gzip, bzip2, and xz, were analyzed and compared in terms of speed and efficiency.

Additionally, an overview of software tools for archiving and compression was provided for both Linux environments and mobile devices. It was determined that each compression algorithm has its own advantages and disadvantages, and the optimal method depends on the user's specific needs—whether prioritizing processing speed or maximizing disk space savings.

Overall, this work provided practical experience in handling archives in Linux, which is a crucial aspect of system administration and managing large amounts of data.
