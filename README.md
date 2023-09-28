# HelloWorldLocalPythonServer
A simple example of a local python server that serves a Hello World static webpage

### Step 1: Clone Repository
Save this respository to a directory of your choice. The only relevant file is `index.html`, which you can replace with whatever static webpage you would like to view.

### Step 2: Start a Local Server using Python

1. Navigate to the directory containing `index.html` using your terminal or command prompt.
   
2. Run the following command:

   ```bash
   python -m http.server 8000
   ```

   This command starts a simple HTTP server on port `8000`. If you want to use a different port, replace `8000` with your desired port number.

3. Open your web browser and navigate to `http://localhost:8000/`. You should see the "Hello, World!" webpage.

### Note:
- This method is suitable for development or local testing purposes but should not be used in a production environment.
- The command might be `python3` instead of `python` on some systems, especially on Linux and macOS where both Python 2 and Python 3 are installed.

#### Remember to press `Ctrl+C` in your terminal or command prompt when you're done to stop the server.
