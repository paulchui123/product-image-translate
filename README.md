# Image Translate API - Image Translation Service

This API provides a simple interface to translate text within images from a source language to a target language. The service accepts an image URL, the source language, and the target language, then returns a translated image URL.
---

### **The API **
[Image Translate API](https://rapidapi.com/paulchui/api/image-translate)


![image](https://i.imgur.com/2mDIdAr.jpg)


### **HTTP Method**
`POST`

### **Parameters**

| Name         | Type   | Required | Description                                                      |
|--------------|--------|----------|------------------------------------------------------------------|
| `image_url`  | String | Yes      | The URL of the image to be translated.                          |
| `source_lang`| String | Yes      | The source language code (e.g., `en` for English).              |
| `target_lang`| String | Yes      | The target language code (e.g., `zh` for Chinese).              |

---
### **Success Response**

| Name         | Type   | Description                                                      |
|--------------|--------|------------------------------------------------------------------|
|ACK           |String  |Acknowledgment of the request. Returns Success.
|translated_image_url|String|URL of the translated image.|

### **Success Response**
```json
{
  "ACK": "Success",
  "translated_image_url": "https://cdn.pecreation.com/r/21db202e1ff94ab487e17ef08bea8f4d.jpg"
}
  ```
  
## Language Codes for English Translation

The API supports translations from **English** (`en`) to the following languages:

| **No.** | **Souce language code**        | **Language Name**              |  **Target Language Code** |
|---------|--------------------------------|--------------------------------|--------------------------------|
| 1       | en                             | Chinese                        | zh                             |
| 2       | en                             | Russian                        | ru                             |
| 3       | en                             | Spanish                        | es                             |
| 4       | en                             | French                         | fr                             |
| 5       | en                             | German                         | de                             |
| 6       | en                             | Italian                        | it                             |
| 7       | en                             | Dutch                          | nl                             |
| 8       | en                             | Portuguese                     | pt                             |
| 9       | en                             | Vietnamese                     | vi                             |
| 10      | en                             | Turkish                        | tr                             |
| 11      | en                             | Malay                          | ms                             |
| 12      | en                             | Thai                           | th                             |
| 13      | en                             | Polish                         | pl                             |
| 14      | en                             | Indonesian                     | id                             |
| 15      | en                             | Japanese                       | ja                             |
| 16      | en                             | Korean                         | ko                             |


[Image Translate API](https://rapidapi.com/paulchui/api/image-translate)
