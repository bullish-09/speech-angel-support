---
layout: default
title: "SpeechAngel Privacy Policy"
---

# SpeechAngel Privacy Policy

**Effective Date:** June 10, 2026

At SpeechAngel, we believe your presentations and conversations are strictly your business. We designed our application from the ground up with privacy as the core feature. This Privacy Policy outlines how we handle your data when you use the SpeechAngel iOS application.

## 1. On-Device Processing
SpeechAngel is fundamentally an offline-first application. All core processing, including our Large Language Model (LLM) analysis and presentation tracking, happens entirely on your device.

*   **No Cloud Servers:** We do not send your documents, speaker notes, or audio transcripts to any proprietary cloud servers for processing or storage.
*   **On-Device AI:** The intelligence that powers SpeechAngel (using Google's Gemma via LiteRT) runs locally on your iPhone's hardware.

## 2. Data We Access and Why
To function effectively, SpeechAngel requires access to specific device features:

*   **Microphone (Audio Input):** We require microphone access to listen to your presentations and provide real-time tracking and feedback. 
    *   *How it's used:* Your audio is processed locally using Apple's Native Speech framework configured for on-device recognition wherever supported by the OS.
    *   *Storage:* We do not record or save the raw audio files. We only temporarily store the text transcript of your presentation to provide grading and history within the app.
*   **Camera (Vision Processing - Wearables Build Only):** If using the SpeechAngel Wearables integration with Meta Glasses, the app receives periodic camera frames.
    *   *How it's used:* These frames are used solely to synchronize your position in the presentation by comparing them to your slide deck.
    *   *Storage:* Camera frames are processed in memory and are discarded immediately. They are never saved, stored, or transmitted.
*   **Local Storage (Documents):** When you import a PDF or PPTX file into the app, it is stored in the app's local sandbox on your device.
    *   *Storage:* You retain full control over these documents. You can delete them at any time, which will permanently remove the document, its extracted notes, and its associated presentation history from your device.

## 3. Data Collection and Tracking
*   **No Account Required:** You do not need to create an account or provide an email address to use SpeechAngel.
*   **No Analytics or Ad Tracking:** We do not track your usage behavior, sell your data, or include any third-party advertising or analytics SDKs that profile you.

## 4. Third-Party Integrations
*   **Apple iOS Frameworks:** We utilize native iOS frameworks (like `SFSpeechRecognizer` and the `Vision` framework). While we request on-device processing, some underlying OS functions may behave according to your global Apple privacy settings.
*   **Meta Wearables SDK:** For users of the Wearables build, the app interacts with the Meta Wearables SDK to communicate with your glasses. This connection is local (Bluetooth/Local Network) between your phone and the glasses.

## 5. Changes to This Policy
We may update our Privacy Policy from time to time if we add new features or if required by law. We will notify you of any changes by posting the new Privacy Policy within the app and updating the "Effective Date" at the top.

## 6. Contact Us
If you have any questions or suggestions about our Privacy Policy, do not hesitate to contact us at overseehub.support@gmail.com.
