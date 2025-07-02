

# 📝 OCR with Google Vision — OpenRPA Example

This example demonstrates how to use **Google Vision OCR** within an OpenRPA workflow to extract text from images or PDF files.

## 📌 What’s Included

* Example OpenRPA workflow file.
* Sample images for testing OCR.
* Documentation on how to configure and run the bot.

## ⚡ Prerequisites

* [OpenRPA](https://openrpa.openiap.io/) installed and configured.
* A **Google Cloud Vision API** key.
* Internet access (for Google Cloud API calls).

## 🔑 Setting up Google Vision

1️⃣ Create a Google Cloud project: [https://console.cloud.google.com/](https://console.cloud.google.com/)

2️⃣ Enable the **Vision API** for your project.

3️⃣ Generate a service account key (JSON file).

4️⃣ Set the environment variable:

```bash
GOOGLE_APPLICATION_CREDENTIALS=/path/to/your/service-account-key.json
```

## 🚀 Running the Example

1️⃣ Open OpenRPA.

2️⃣ Import the provided workflow file:

```
ocr-with-google-vision.xaml
```

3️⃣ Update the path or file name as needed inside the workflow.

4️⃣ Run the workflow. The extracted text will be shown or stored according to the flow design.

## 🗂 Example Structure

```
ocr-with-google-vision/
├── google_vision_with_ocr.xaml       # The OpenRPA workflow
├── README.md                         # (You’re reading this!)
```

## 🤝 Contributing

Feel free to submit pull requests or open issues for improvements.

## 📄 License

This example is provided under the MIT License. See [LICENSE](https://github.com/open-rpa/examples-files/blob/master/LICENSE).

