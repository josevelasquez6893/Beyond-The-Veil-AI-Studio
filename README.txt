BEYOND THE VEIL AI STUDIO - ANDROID SOURCE PROJECT

This is an Android Studio project, not a compiled APK.
Open this folder in Android Studio, allow Gradle sync, then Build > Build Bundle(s) / APK(s) > Build APK(s).

AI video connection:
- In the app, open Engine setup.
- Enter a compatible Hugging Face Gradio Space ID (owner/name).
- Enter the exact API endpoint name from that Space's "Use via API" panel.
- Set the JSON input array in the same order and shape as the Space API schema. Use {{prompt}} where the prompt should be inserted.
- A Hugging Face token is optional for some public Spaces; only use a read-only token and keep this personal phone secure.

IMPORTANT:
- Hugging Face ZeroGPU free quota is limited; queue delays apply.
- Every Space has its own API schema and outputs. This generic Gradio queue connector requires a compatible endpoint returning a video path/URL.
- The app does not add payment methods or use paid inference by design.
- A one-hour movie must be assembled from many short generated clips in a separate video editor.
- This project is provided as source. It has not been compiled or tested on a physical Android phone in this environment.
