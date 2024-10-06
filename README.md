<!DOCTYPE html>
<html lang="ur">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title id="page-title">تاریخی مضامین - پاکستان</title>
    <style>
        body {
            font-family: 'Urdu Nash Talikh', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9; /* Light background */
            color: #333; /* Dark text */
        }
        header {
            background: green; /* Green header */
            color: white;
            padding: 20px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }
        h1, h2, h3 {
            background-color: green; /* Green background for headings */
            color: #fff; /* White text for headings */
            text-align: center; /* Center align all headings */
            padding: 10px; /* Padding for better appearance */
            border-radius: 5px; /* Rounded corners for headings */
        }
        .content {
            display: flex;
            align-items: flex-start; /* Align items to the start */
            margin-bottom: 20px;
        }
        .content img {
            width: 150px; /* Set a fixed width for images */
            height: auto; /* Maintain aspect ratio */
            margin-left: 20px; /* Space between text and image */
        }
        footer {
            text-align: center;
            padding: 20px 0;
            background: #f1f1f1; /* Light footer background */
            margin-top: 20px;
        }
        @media (max-width: 600px) {
            nav {
                display: flex;
                flex-direction: column;
                align-items: center;
            }
            nav a {
                margin: 10px 0;
            }
            .content {
                flex-direction: column; /* Stack text and image on small screens */
                align-items: center; /* Center align items */
            }
            .content img {
                margin-left: 0; /* Remove left margin for images */
                margin-top: 10px; /* Add top margin for images */
                width: 100%; /* Make images responsive */
                max-width: 300px; /* Set max width for images */
            }
        }
    </style>
    <script>
        const translations = {
            en: {
                title: "Historical Articles - Pakistan",
                home: "Home",
                contact: "Contact Us",
                articles: "Articles",
                history: "History of Pakistan",
                introduction: "The history of Pakistan encompasses a long and diverse journey. This land has been a center of ancient civilizations, including Mohenjo-Daro and Harappa.",
                earlyPeriod: "Early Period",
                earlyDescription: "The civilizations of Mohenjo-Daro and Harappa thrived around 2500 BCE. These cities were centers of agriculture, trade, and cultural development.",
                muslimEra: "Muslim Era",
                muslimDescription: "With the arrival of the Arabs in the 8th century, Islam began to spread in this region. Later, various Muslim empires, such as the Ghaznavids, Ghurids, and Mughals, ruled this land. The Mughal Empire achieved significant successes in culture, art, and knowledge.",
                britishRaj: "British Raj",
                britishDescription: "In the 19th century, the British Empire gained control over this region. During British rule, Muslims began to struggle for the protection of their identity.",
                creationOfPakistan: "Creation of Pakistan",
                creationDescription: "In 1947, with the partition of India, Pakistan was established. Under the leadership of Quaid-e-Azam Muhammad Ali Jinnah, Muslims struggled for the establishment of a separate state.",
                modernEra: "Modern Era",
                modernDescription: "The history of Pakistan includes several challenges, such as political instability, economic issues, and terrorism. However, this country has made progress both domestically and internationally.",
                summary: "Summary",
                summaryDescription: "The history of Pakistan is a blend of deep cultural heritage and various civilizations. This land is still on the path of development, and studying its history helps us understand its culture and identity.",
                contact: "Contact Us",
                name: "Name:",
                email: "Email:",
                message: "Message:",
                submit: "Submit",
                footer: "© 2024 Historical Articles. All rights reserved."
            },
            ur: {
                title: "تاریخی مضامین - پاکستان",
                home: "ہوم",
                contact: "ہم سے رابطہ کریں",
                articles: "مضامین",
                history: "پاکستان کی تاریخ",
                introduction: "پاکستان کی تاریخ ایک طویل اور متنوع سفر کا احاطہ کرتی ہے۔ یہ سرزمین قدیم تہذیبوں کا مرکز رہی ہے، جن میں موہنجو داڑو اور ہڑپہ کی تہذیب شامل ہیں۔",
                earlyPeriod: "ابتدائی دور",
                earlyDescription: "موہنجو داڑو اور ہڑپہ کی تہذیبیں تقریباً 2500 قبل مسیح کے ارد گرد پھلی پھولیں۔ یہ شہر زراعت، تجارت، اور ثقافتی ترقی کے مراکز تھے۔",
                muslimEra: "مسلم دور",
                muslimDescription: "8ویں صدی میں عربوں کی آمد کے ساتھ، اس خطے میں اسلام کا آغاز ہوا۔ بعد میں، مختلف مسلم سلطنتیں، جیسے کہ غزنوی، غوری، اور مغل، نے اس سرزمین پر حکمرانی کی۔ مغل سلطنت نے ثقافت، فن، اور علم کے میدان میں نمایاں کامیابیاں حاصل کیں۔",
                britishRaj: "برطانوی راج",
                britishDescription: "19ویں صدی میں، برطانوی سلطنت نے اس خطے پر کنٹرول حاصل کر لیا۔ برطانوی حکومت کے دوران، مسلمانوں نے اپنی شناخت کے تحفظ کے لیے جدوجہد شروع کی۔",
                creationOfPakistan: "قیام پاکستان",
                creationDescription: "1947 میں، ہندوستان کی تقسیم کے ساتھ، پاکستان کا قیام عمل میں آیا۔ قائداعظم محمد علی جناح کی قیادت میں، مسلمانوں نے ایک علیحدہ ریاست کے قیام کی جدوجہد کی۔",
                modernEra: "جدید دور",
                modernDescription: "پاکستان کی تاریخ میں کئی چیلنجز شامل ہیں، جیسے کہ سیاسی عدم استحکام، اقتصادی مسائل، اور دہشت گردی۔ تاہم، اس ملک نے اپنی سرحدوں کے اندر اور بین الاقوامی سطح پر ترقی کی ہے۔",
                summary: "خلاصہ",
                summaryDescription: "پاکستان کی تاریخ ایک گہرے ثقافتی ورثے اور مختلف تہذیبوں کا میل ہے۔ یہ سرزمین آج بھی ترقی کی راہ پر گامزن ہے، اور اس کی تاریخ کا مطالعہ ہمیں اس کی ثقافت اور شناخت کو سمجھنے میں مدد دیتا ہے۔",
                contact: "ہم سے رابطہ کریں",
                name: "نام:",
                email: "ای میل:",
                message: "پیغام:",
                submit: "جمع کریں",
                footer: "© 2024 تاریخی مضامین. تمام حقوق محفوظ ہیں۔"
            },
            hi: {
                title: "ऐतिहासिक लेख - पाकिस्तान",
                home: "घर",
                contact: "संपर्क करें",
                articles: "लेख",
                history: "पाकिस्तान का इतिहास",
                introduction: "पाकिस्तान का इतिहास एक लंबी और विविध यात्रा को समेटे हुए है। यह भूमि प्राचीन सभ्यताओं का केंद्र रही है, जिसमें मोहनजोदड़ो और हड़प्पा की सभ्यता शामिल हैं।",
                earlyPeriod: "प्रारंभिक काल",
                earlyDescription: "मोहनजोदड़ो और हड़प्पा की सभ्यताएँ लगभग 2500 ईसा पूर्व के आस-पास विकसित हुईं। ये शहर कृषि, व्यापार, और सांस्कृतिक विकास के केंद्र थे।",
                muslimEra: "मुस्लिम युग",
                muslimDescription: "8वीं सदी में अरबों के आगमन के साथ, इस क्षेत्र में इस्लाम का आगाज़ हुआ। बाद में, विभिन्न मुस्लिम साम्राज्यों, जैसे ग़ज़नवी, ग़ौरी, और मुग़ल, ने इस भूमि पर शासन किया। मुग़ल साम्राज्य ने संस्कृति, कला, और ज्ञान के क्षेत्र में महत्वपूर्ण सफलताएँ हासिल कीं।",
                britishRaj: "ब्रिटिश राज",
                britishDescription: "19वीं सदी में, ब्रिटिश साम्राज्य ने इस क्षेत्र पर नियंत्रण हासिल किया। ब्रिटिश शासन के दौरान, मुसलमानों ने अपनी पहचान के संरक्षण के लिए संघर्ष किया।",
                creationOfPakistan: "पाकिस्तान का निर्माण",
                creationDescription: "1947 में, भारत के विभाजन के साथ, पाकिस्तान की स्थापना हुई। क़ायदा ए आज़म मुहम्मद अली जिन्ना के नेतृत्व में, मुसलमानों ने एक अलग राज्य की स्थापना के लिए संघर्ष किया।",
                modernEra: "आधुनिक युग",
                modernDescription: "पाकिस्तान के इतिहास में कई चुनौतियाँ शामिल हैं, जैसे राजनीतिक अस्थिरता, आर्थिक समस्याएँ, और आतंकवाद। हालाँकि, यह देश घरेलू और अंतरराष्ट्रीय स्तर पर प्रगति कर चुका है।",
                summary: "सारांश",
                summaryDescription: "पाकिस्तान का इतिहास गहरे सांस्कृतिक विरासत और विभिन्न सभ्यताओं का मिश्रण है। यह भूमि आज भी विकास के मार्ग पर अग्रसर है, और इसके इतिहास का अध्ययन हमें इसकी संस्कृति और पहचान को समझने में मदद करता है।",
                contact: "संपर्क करें",
                name: "नाम:",
                email: "ईमेल:",
                message: "संदेश:",
                submit: "जमा करें",
                footer: "© 2024 ऐतिहासिक लेख. सभी अधिकार सुरक्षित।"
            },
            ar: {
                title: "مقالات تاريخية - باكستان",
                home: "الرئيسية",
                contact: "تواصل معنا",
                articles: "مقالات",
                history: "تاريخ باكستان",
                introduction: "يغطي تاريخ باكستان رحلة طويلة ومتنوعة. كانت هذه الأرض مركزًا للحضارات القديمة، بما في ذلك موهينجو دارو وهارابا.",
                earlyPeriod: "الفترة المبكرة",
                earlyDescription: "ازدهرت حضارات موهينجو دارو وهارابا حوالي 2500 قبل الميلاد. كانت هذه المدن مراكز للزراعة والتجارة والتنمية الثقافية.",
                muslimEra: "العصر الإسلامي",
                muslimDescription: "مع وصول العرب في القرن الثامن، بدأ الإسلام ينتشر في هذه المنطقة. لاحقًا، حكمت إمبراطوريات إسلامية مختلفة، مثل الغزنويين والغوريين والمغول، هذه الأرض. حققت الإمبراطورية المغولية نجاحات كبيرة في الثقافة والفن والعلم.",
                britishRaj: "الراج البريطاني",
                britishDescription: "في القرن التاسع عشر، حصل الإمبراطورية البريطانية على السيطرة على هذه المنطقة. خلال الحكم البريطاني، بدأ المسلمون في النضال من أجل حماية هويتهم.",
                creationOfPakistan: "تأسيس باكستان",
                creationDescription: "في عام 1947، مع تقسيم الهند، تم تأسيس باكستان. تحت قيادة القائد الأعظم محمد علي جناح، ناضل المسلمون من أجل إقامة دولة منفصلة.",
                modernEra: "العصر الحديث",
                modernDescription: "يتضمن تاريخ باكستان العديد من التحديات، مثل عدم الاستقرار السياسي والمشاكل الاقتصادية والإرهاب. ومع ذلك، حقق هذا البلد تقدمًا على الصعيدين المحلي والدولي.",
                summary: "ملخص",
                summaryDescription: "تاريخ باكستان هو مزيج من التراث الثقافي العميق والحضارات المختلفة. لا تزال هذه الأرض في طريق التنمية، ويساعدنا دراسة تاريخها في فهم ثقافتها وهويتها.",
                contact: "تواصل معنا",
                name: "الاسم:",
                email: "البريد الإلكتروني:",
                message: "رسالة:",
                submit: "إرسال",
                footer: "© 2024 مقالات تاريخية. جميع الحقوق محفوظة."
            }
        };

        function changeLanguage(language) {
            document.getElementById('page-title').innerText = translations[language].title;

            document.getElementById('home-link').innerText = translations[language].home;
            document.getElementById('contact-link').innerText = translations[language].contact;
            document.getElementById('articles-link').innerText = translations[language].articles;

            document.getElementById('history-title').innerText = translations[language].history;
            document.getElementById('introduction').innerText = translations[language].introduction;
            document.getElementById('early-title').innerText = translations[language].earlyPeriod;
            document.getElementById('early-description').innerText = translations[language].earlyDescription;
            document.getElementById('muslim-title').innerText = translations[language].muslimEra;
            document.getElementById('muslim-description').innerText = translations[language].muslimDescription;
            document.getElementById('british-title').innerText = translations[language].britishRaj;
            document.getElementById('british-description').innerText = translations[language].britishDescription;
            document.getElementById('creation-title').innerText = translations[language].creationOfPakistan;
            document.getElementById('creation-description').innerText = translations[language].creationDescription;
            document.getElementById('modern-title').innerText = translations[language].modernEra;
            document.getElementById('modern-description').innerText = translations[language].modernDescription;
            document.getElementById('summary-title').innerText = translations[language].summary;
            document.getElementById('summary-description').innerText = translations[language].summaryDescription;

            document.getElementById('contact-title').innerText = translations[language].contact;
            document.getElementById('name-label').innerText = translations[language].name;
            document.getElementById('email-label').innerText = translations[language].email;
            document.getElementById('message-label').innerText = translations[language].message;
            document.getElementById('submit-button').innerText = translations[language].submit;
            document.getElementById('footer-text').innerText = translations[language].footer;
        }
    </script>
</head>
<body>

<header>
    <h1 id="page-title">Article</h1>
    <nav>
        <a href="#home" id="home-link">ہوم</a>
        <a href="#contact" id="contact-link">ہم سے رابطہ کریں</a>
        <a href="#blog" id="articles-link">مضامین</a>
    </nav>
    <select onchange="changeLanguage(this.value)">
        <option value="ur">اردو</option>
        <option value="en">English</option>
        <option value="hi">हिन्दी</option>
        <option value="ar">العربية</option>
    </select>
</header>

<div class="container">
    <section id="home">
        <h2 id="history-title">پاکستان کی تاریخ</h2>
        <div class="content">
            <p id="introduction">پاکستان کی تاریخ ایک طویل اور متنوع سفر کا احاطہ کرتی ہے۔ یہ سرزمین قدیم تہذیبوں کا مرکز رہی ہے، جن میں موہنجو داڑو اور ہڑپہ کی تہذیب شامل ہیں۔</p>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFAzNuzp95dffzE8V5NN_pHq2XuapNQNsynQ&s" alt="موہنجو داڑو">
        </div>

        <h3 id="early-title">ابتدائی دور</h3>
        <div class="content">
            <p id="early-description">موہنجو داڑو اور ہڑپہ کی تہذیبیں تقریباً 2500 قبل مسیح کے ارد گرد پھلی پھولیں۔ یہ شہر زراعت، تجارت، اور ثقافتی ترقی کے مراکز تھے۔</p>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTZk7x89OYEUZHmNPh2tMJ4HZFsTWuFdaJQgg&s" alt="ہڑپہ">
        </div>

        <h3 id="muslim-title">مسلم دور</h3>
        <div class="content">
            <p id="muslim-description">8ویں صدی میں عربوں کی آمد کے ساتھ، اس خطے میں اسلام کا آغاز ہوا۔ بعد میں، مختلف مسلم سلطنتیں، جیسے کہ غزنوی، غوری، اور مغل، نے اس سرزمین پر حکمرانی کی۔ مغل سلطنت نے ثقافت، فن، اور علم کے میدان میں نمایاں کامیابیاں حاصل کیں۔</p>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRlQMvzpZa1GR_dmNf0aRwWgU0SJSOXLG1neg&s" alt="مسلم دور">
        </div>

        <h3 id="british-title">برطانوی راج</h3>
        <div class="content">
            <p id="british-description">19ویں صدی میں، برطانوی سلطنت نے اس خطے پر کنٹرول حاصل کر لیا۔ برطانوی حکومت کے دوران، مسلمانوں نے اپنی شناخت کے تحفظ کے لیے جدوجہد شروع کی۔</p>
            <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSobl4gBuAwKA8kK1hmpadm1ILYKWbw-dzB8Q&s" alt="برطانوی راج">
        </div>

        <h3 id="creation-title">قیام پاکستان</h3>
        <div class="content
