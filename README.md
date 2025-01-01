## 🏃‍♂️ Running the FastAPI Application

/yt-api-python

To run the FastAPI application (`app.py`), follow these steps:

1. Install the required dependencies:
   ```bash
   python -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

2. Run the FastAPI application:
   ```bash
   python app.py
   ```

3. Access the application in your web browser at `http://localhost:3001`.

4. To authenticate and grant permissions for uploading videos to YouTube:
   - Visit `http://localhost:3001/auth` and follow the authentication flow.
   - After successful authentication, you will be redirected to the upload page.

5. To upload a video:
   - Go to `http://localhost:3001/upload`.
   - Fill in the video details (title, description, tags, privacy status).
   - Select a video file to upload.
   - Click the "Upload" button to start the upload process.

6. To retrieve information about your YouTube channel:
   - Make a GET request to `http://localhost:3001/channel-info`.
   - The response will contain details about your channel.

That's it! You're now ready to use the JoyVASA monorepo and explore its features. Happy auto-creating! 🎉

If you encounter any issues or have questions, feel free to reach out to the project maintainers. 📧

```
Note: The above instructions assume a Linux-based environment. Adjust the commands accordingly for other operating systems.
```

🌟 Enjoy! 🚀