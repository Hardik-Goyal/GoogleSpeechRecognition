# GoogleSpeechRecognition

Video:
[Speech to Text using Google's API in Node.js](https://youtu.be/kGVKzp3JWJU)

Using Google Cloud API service by using Google Client Libraries.

---

This is an example of Speech To Text program.

Other features like Speaker Diarization that is Speaker Recognition, Speech Adaptation can be added by adding properties in config object.

Example adding speaker recognition config object code will be: 
const config = {

  * encoding: 'LINEAR16',
  * sampleRateHertz: 8000,
  * languageCode: 'en-US',
  * enableSpeakerDiarization: true,
  * diarizationSpeakerCount: 2,
  * model: 'phone_call', <br>
};

---

> Audio Transcription is not 100% correct if you notice carefully in last few sentences. Reason being you have to adjust other audio properties like language accent, etc.

---

Resource Links: <br>
[Quickstart](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbTRGWDc2aVNPOHBUaEt0TVJDbXE5cVMzazZrQXxBQ3Jtc0trVVZDcVp2R09weDVTVW92Z0J5YW8zVFhpYWR3REI4TGZGUDRveEltMTBHXzBxRVFuSGFTdVNwVDBNVGU3WjM5TzBxSTBaV2Z0TkU0RGZSa1ZuVl9hLVZDZG5wMHRhNTNYN1N3ZVFJaGVVVnEzTFlNMA&q=https%3A%2F%2Fcloud.google.com%2Fspeech-to-text%2Fdocs%2Fquickstart-client-libraries)

[JS Objects](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqblE3eEVUSklubkZSU2sxTWhEX00ybENscjVRZ3xBQ3Jtc0tramk4U3docTZ1bXNSS01aeUdnX1FSSUlORTFJZEpkWW9jM2VuRmk0c2dHeXdQOHhJalBqbVo0cXZ4OEswYVpEUG9iMUlsVG9OeGtqV1B6LTVmaC1oTXRMU2U4XzEwRFNkZG1ybHJWdDZVcWs0VEJCaw&q=https%3A%2F%2Fwww.w3schools.com%2Fjs%2Fjs_objects.asp)


