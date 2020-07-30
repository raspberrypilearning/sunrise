## सूर्योदय सजीव करणे

आपला सूर्योदय सजीव करण्यासाठी, सूर्य कसे फिरते आणि किती वेळ लागतो हे आपण परिभाषित करणे आवश्यक आहे.

हे करण्यासाठी आपण **key frames** list परिभाषित करता. प्रत्येक की फ्रेम एनिमेशनमधील विशिष्ट बिंदूवर घटकाची CSS गुणधर्म परिभाषित करते.

+ प्रथम, आपल्याला `@keyframes` वापरण्याची आवश्यकता आहे, सूर्योदय नावाचे नवीन एनिमेशन तयार करण्यासाठी.
    
    हा CSS कोड आपल्या फाईल `style.css` शेवटी जोडा:
    
        @keyframes sunrise {
            0%
            100%
        }
        
    
    हा कोड सूर्याला सांगत आहे की सुरवातीस स्वतः कोठे ठेवावे (`0%`) आणि शेवट (`100%`) अ‍ॅनिमेशनची.
    
    कारण सूर्य आकाशात आहे `div`, `top` आणि `left` आपण दिलेली पोझिशन्स सह, आकाशात आहेत `top: 100%` आकाशाचे तळाशी असून वेबपृष्ठाच्या तळाशी नाही.

+ आता आपण `सूर्योदय` अ‍ॅनिमेशन तयार केला, आपल्याला आपल्या सूर्याला ते वापरण्यास सांगावे लागेल!
    
    हायलाइट केलेला कोड आपल्या सूर्याच्या CSS मध्ये जोडा:
    
    ![screenshot](images/sunrise-sunrise.png)
    
    हे सूर्योदय एनिमेट करण्यासाठी 10 सेकंद घालविण्यास सूर्यास सांगते.

+ पुन्हा अ‍ॅनिमेशन Trinket मध्ये चालविण्यासाठी, फक्त **Autorun** क्लिक करा.