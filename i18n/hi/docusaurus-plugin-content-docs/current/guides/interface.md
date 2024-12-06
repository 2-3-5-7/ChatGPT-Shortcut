# इंटरफ़ेस विवरण

AiShort सभी सुझाए गए शब्दों को प्रदर्शित करने में चूक करता है। पृष्ठ को तीन वर्गों में विभाजित किया गया है: टैग क्षेत्र, खोज क्षेत्र और सुझाए गए शब्द प्रदर्शन क्षेत्र।

![](https://img.newzone.top/2023-06-05-20-44-19.png?imageMogr2/format/webp)

## 🏷टैग फ़िल्टरिंग

टैग क्षेत्र को सुझाए गए शब्दों के डोमेन और कार्यक्षमता के आधार पर विभाजित किया गया है, जिससे विभिन्न परिदृश्यों और आवश्यकताओं के आधार पर चयन की अनुमति मिलती है। इसका उपयोग मल्टी-टैग फ़िल्टरिंग करने के लिए टैग क्षेत्र के ऊपरी दाएं कोने में "टैग फ़िल्टरिंग नियम टॉगल" बटन के साथ किया जा सकता है। डिफ़ॉल्ट स्थिति ओआर है, जो चुने हुए टैग के तहत सभी सुझाए गए शब्दों का चयन करती है। AND पर स्विच करने से सुझाए गए शब्द फ़िल्टर हो जाएंगे जिनमें कई चयनित टैग हैं।

![](https://img.newzone.top/2023-06-05-20-50-19.png?imageMogr2/format/webp)

## 🔍 कीवर्ड खोज

कीवर्ड खोज क्षेत्र में सुझाए गए शब्दों के शीर्षक, सारांश, सामग्री और आपकी मूल भाषा में अनुवाद शामिल हैं. कीवर्ड दर्ज करने के बाद, सुझाए गए शब्द प्रदर्शन क्षेत्र तुरंत फ़िल्टर की गई सामग्री दिखाएगा। यदि टैग्स का चयन कर लिया गया है, तो कीवर्ड खोज चयनित टैग्स के दायरे तक सीमित होगी. पीसी की तरफ, खोज बॉक्स में सामग्री बदलने के बाद, नए खोज परिणाम 800 मिलीसेकंड के बाद प्रदर्शित होंगे। मोबाइल उपकरणों पर, यह तुरंत अपडेट हो जाता है।

![](https://img.newzone.top/2023-06-05-20-58-07.png?imageMogr2/format/webp)

लॉग इन करने के बाद, खोज क्षेत्र में आपके द्वारा सबमिट किए गए और एकत्र किए गए संकेत शामिल होंगे।

![](https://img.newzone.top/2024-08-12-20-38-27.png?imageMogr2/format/webp)

## 🔬 शीघ्र प्रतिलिपि

टैग फ़िल्टरिंग और कीवर्ड खोज के माध्यम से, कार्ड के ऊपरी दाएं कोने में "कॉपी करें" बटन पर क्लिक करने से आप सुझाए गए शब्दों को प्राप्त कर सकते हैं। उन्हें ChatGPT में चिपकाने के बाद, आप सुझावों का उल्लेख कर सकते हैं और वांछित डोमेन में उत्तर प्राप्त करने के लिए अपनी विशिष्ट आवश्यकताओं के अनुसार पाठ को समायोजित कर सकते हैं। यदि सुझाए गए शब्दों में मूल भाषा स्पष्टीकरण स्पष्ट नहीं है, तो आप स्रोत वेबपेज देखने के लिए सुझाए गए शब्दों के निचले दाएं कोने में लिंक पर क्लिक कर सकते हैं।

![](https://img.newzone.top/2023-06-11-17-14-07.png?imageMogr2/format/webp)

## 💬 भाषा परिवर्तन

डिफ़ॉल्ट रूप से, सुझाए गए शब्द अंग्रेजी में प्रदर्शित होते हैं। यदि आप एक गैर-अंग्रेजी पृष्ठ का उपयोग कर रहे हैं और अपनी मूल भाषा में व्याख्याओं को देखना चाहते हैं, तो कृपया गैर-अंग्रेजी भाषा में स्विच करने के लिए सुझाए गए शब्द सामग्री पर क्लिक करें, और अंग्रेजी में वापस स्विच करने के लिए फिर से क्लिक करें। कृपया ध्यान दें कि भाषा स्विचिंग केवल तभी काम करती है जब प्रॉम्प्ट में पाठ पर क्लिक किया जाता है, और रिक्त क्षेत्र में क्लिक करना अप्रभावी होता है।

![चीनी और अंग्रेजी के बीच स्विच करना](http://img.newzone.top/chatgptshortcut_encn.gif)

यदि आप चाहते हैं कि सुझाए गए शब्द डिफ़ॉल्ट रूप से आपकी मूल भाषा में प्रदर्शित हों, तो आप टैग क्षेत्र के ऊपरी दाएं कोने में "स्विच प्रॉम्प्ट भाषा" बटन पर क्लिक कर सकते हैं। हालांकि, कृपया ध्यान दें कि मूल भाषा अनुवाद पर स्विच करते समय भी, कॉपी बटन केवल अंग्रेजी सुझाए गए शब्दों की प्रतिलिपि बनाता है।

## 🔥 लोकप्रिय सॉर्टिंग

पृष्ठ अब शीघ्र उपयोग की आवृत्ति प्रदर्शित करता है, और उच्च उपयोग आवृत्ति वाले संकेतों को "पसंदीदा" के रूप में चिह्नित किया जाएगा। इसके अतिरिक्त, प्रॉम्प्ट टैग की छंटाई मुख्य रूप से गर्मी मूल्य पर आधारित होगी। गर्मी मान समय-समय पर अद्यतन किया जाएगा।