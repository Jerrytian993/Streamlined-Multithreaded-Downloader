Streamlined-Multithreaded-Downloader is a Java application designed to download files efficiently by accepting a URL from the user or as a command-line argument. The application supports concurrent downloads, improving performance and user experience.

Features
- Multithreaded Downloads: Leverages thread pooling to handle multiple downloads simultaneously, reducing overall download time.
- User-friendly Input: Accepts URL input either from the user through a prompt or as a command-line argument.
Real-time Logging: Provides real-time feedback with log outputs to ensure users stay informed about the progress of their downloads.
- Error Handling: Built-in mechanisms to handle network issues and interruptions, ensuring download resilience.
- Requirements : Java 8 or higher

How to Run
- Command Line
- Clone or download the repository.
- Navigate to the project directory.
- Compile the Java files:
"javac -d bin src/com/bjpowernode/*.java"
- Run the application:
"java -cp bin com.bjpowernode.Main <URL>"(Replace <URL> with the download link for the file.)
Interactive Mode
-If no URL is passed as an argument, the application will prompt you to enter the download URL.
- Simply input the URL when prompted, and the application will handle the rest.
