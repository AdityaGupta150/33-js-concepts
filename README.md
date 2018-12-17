<h1 align="center">
<br>
  <a href="https://github.com/leonardomso/33"><img src="https://i.imgur.com/dsHmk6H.jpg" alt="33 Concepts Every JS Developer Should Know" width=200"></a>
  <br>
    <br>
  33 संकल्पना प्रत्येक जावास्क्रिप्ट डेवलपर को पता होना चाहिए
  <br><br>
</h1>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square" alt="License MIT">
  </a>
  <a href="https://travis-ci.com/leonardomso/33-js-concepts">
    <img src="https://img.shields.io/travis/leonardomso/33-js-concepts/master.svg?style=flat-square&label=build&logo=travis" alt="Build Status">
  </a>
</p>

## परिचय

यह संग्रह जावास्क्रिप्ट में अपनी अवधारणाओं को मास्टर करने में मदद करने के इरादे से बनाया गया था। यह एक आवश्यकता नहीं है, लेकिन भविष्य के अध्ययन के लिए एक गाइड है। यह एक लेख पर आधारित है [स्टीफन कर्टिस](https://twitter.com/stephenthecurt) और आप इसे पढ़ सकते हैं [यहाँ](https://medium.com/@stephenthecurt/33-fundamentals-every-javascript-developer-should-know-13dd720a90d1).

**🚀 गिटहब द्वारा एक के रूप में माना जाता है [2018 की शीर्ष ओपन सोर्स परियोजनाएं!](https://blog.github.com/2018-12-13-new-open-source-projects/)**

## समुदाय

एक पीआर जमा करने के लिए स्वतंत्र महसूस करें अपने स्वयं के रिकैप्स या समीक्षाओं के लिए एक लिंक जोड़ना। यदि आप रेपो को अपनी मूल भाषा में अनुवाद करना चाहते हैं, तो कृपया ऐसा करने में संकोच न करें।

इस रेपो के लिए सभी अनुवाद नीचे सूचीबद्ध होंगे:

- [Chinese](https://github.com/stephentian/33-js-concepts) — Re Tian
- [Portuguese-BR](https://github.com/tiagoboeing/33-js-concepts) — Tiago Boeing
- [Korean](https://github.com/yjs03057/33-js-concepts.git) — Suin Lee
- [Spanish](https://github.com/adonismendozaperez/33-js-conceptos) — Adonis Mendoza
- [Turkish](https://github.com/ilker0/33-js-concepts) — İlker Demir
- [Russian](https://github.com/gumennii/33-js-concepts) — Mihail Gumennii
- [Tiếng Việt](https://github.com/nguyentranchung/33-js-concepts) — Nguyễn Trần Chung
- [Polish](https://github.com/lip3k/33-js-concepts) — Dawid Lipinski
- [Persian](https://github.com/majidalavizadeh/33-js-concepts) — Majid Alavizadeh
- [Indonesian](https://github.com/rijdz/33-js-concepts) — Rijdzuan Sampoerna
- [Hindi](https://github.com/vikaschauhan/33-js-concepts) — Vikas Chauhan 

---

## विषय - सूची

1. **[Call Stack](#1-call-stack)**
2. **[Primitive Types](#2-primitive-types)**
3. **[Value Types and Reference Types](#3-value-types-and-reference-types)**
4. **[Implicit, Explicit, Nominal, Structuring and Duck Typing](#4-implicit-explicit-nominal-structuring-and-duck-typing)**
5. **[== vs === vs typeof](#5--vs--vs-typeof)**
6. **[Function Scope, Block Scope and Lexical Scope](#6-function-scope-block-scope-and-lexical-scope)**
7. **[Expression vs Statement](#7-expression-vs-statement)**
8. **[IIFE, Modules and Namespaces](#8-iife-modules-and-namespaces)**
9. **[Message Queue and Event Loop](#9-message-queue-and-event-loop)**
10. **[setTimeout, setInterval and requestAnimationFrame](#10-settimeout-setinterval-and-requestanimationframe)**
11. **[JavaScript Engines](#11-javascript-engines)**
12. **[Bitwise Operators, Type Arrays and Array Buffers](#12-bitwise-operators-type-arrays-and-array-buffers)**
13. **[DOM and Layout Trees](#13-dom-and-layout-trees)**
14. **[Factories and Classes](#14-factories-and-classes)**
15. **[this, call, apply and bind](#15-this-call-apply-and-bind)**
16. **[new, Constructor, instanceof and Instances](#16-new-constructor-instanceof-and-instances)**
17. **[Prototype Inheritance and Prototype Chain](#17-prototype-inheritance-and-prototype-chain)**
18. **[Object.create and Object.assign](#18-objectcreate-and-objectassign)**
19. **[map, reduce, filter](#19-map-reduce-filter)**
20. **[Pure Functions, Side Effects and State Mutation](#20-pure-functions-side-effects-and-state-mutation)**
21. **[Closures](#21-closures)**
22. **[High Order Functions](#22-high-order-functions)**
23. **[Recursion](#23-recursion)**
24. **[Collections and Generators](#24-collections-and-generators)**
25. **[Promises](#25-promises)**
26. **[async/await](#26-asyncawait)**
27. **[Data Structures](#27-data-structures)**
28. **[Expensive Operation and Big O Notation](#28-expensive-operation-and-big-o-notation)**
29. **[Algorithms](#29-algorithms)**
30. **[Inheritance, Polymorphism and Code Reuse](#30-inheritance-polymorphism-and-code-reuse)**
31. **[Design Patterns](#31-design-patterns)**
32. **[Partial Applications, Currying, Compose and Pipe](#32-partial-applications-currying-compose-and-pipe)**
33. **[Clean Code](#33-clean-code)**


---

## 1. Call Stack

### सामग्री

 * 📜 [जावास्क्रिप्ट कॉल स्टैक को समझना, इवेंट लूप्स — गौरव पांडविया](https://medium.com/@gaurav.pandvia/understanding-javascript-function-executions-tasks-event-loop-call-stack-more-part-1-5683dea1f5ec)
 * 📜 [जावास्क्रिप्ट कॉल स्टैक को समझना — चार्ल्स फ्रीबर्न](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
 * 📜 [जावास्क्रिप्ट: निष्पादन संदर्भ क्या है? कॉल स्टैक क्या है? — वैलेंटाइनो गैग्लर्डी](https://www.valentinog.com/blog/js-execution-context-call-stack/)
 * 📜 [जेएस इवेंट लूप और कॉल स्टैक क्या है? — जेस टेलफोर्ड](https://gist.github.com/jesstelford/9a35d20a2aa044df8bf241e00d7bc2d0)
 * 📜 [कॉल स्टैक - एमडीएन](https://developer.mozilla.org/en-US/docs/Glossary/Call_stack)
 * 📜 [जावास्क्रिप्ट में निष्पादन संदर्भ और निष्पादन ढेर को समझना — सुखजींदर अरोड़ा](https://blog.bitsrc.io/understanding-execution-context-and-execution-stack-in-javascript-1c9ea8642dd0)
 * 📜 [जावास्क्रिप्ट कैसे काम करता है: इंजन का अवलोकन, रनटाइम, और कॉल स्टैक — अलेक्जेंडर ज़्लाटकोव](https://blog.sessionstack.com/how-does-javascript-actually-work-part-1-b0bacc073cf)
 * 📜 [जावास्क्रिप्ट में निष्पादन संदर्भ, उत्थान, स्कोप्स, और क्लोजर के लिए अंतिम गाइड — टायलर मैकगिनीस](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)

### वीडियो

 * 🎥 [जावास्क्रिप्ट: कॉल स्टैक समझाया — कोडिंग ब्लॉक भारत](https://www.youtube.com/watch?v=w6QGEiQceOM)
 * 🎥 [जेएस कॉल स्टैक 9 मिनट में समझाया गया — कोल्ट स्टील](https://www.youtube.com/watch?v=W8AeMrVtFLY)
 * 🎥 [जावास्क्रिप्ट निष्पादन ढेर — कोडेकैडी](https://www.youtube.com/watch?v=jT0USJeNFEA)
 * 🎥 [कॉल स्टैक क्या है? — एरिक ट्रब](https://www.youtube.com/watch?v=w7QWQlkLY_s)
 * 🎥 [कॉल स्टैक — केविन ड्रम](https://www.youtube.com/watch?v=Q2sFmqvpBe0)
 * 🎥 [जावास्क्रिप्ट निष्पादन को समझना — कोड्समिथ](https://www.youtube.com/watch?v=Z6a1cLyq7Ac&list=PLWrQZnG8l0E4kd1T_nyuVoxQUaYEWFgcD)
 * 🎥 [कॉल स्टैक एंड इवेंट लूप — मूवीज़ कॉम](https://www.youtube.com/watch?v=mk0lu9MKBto)
 * 🎥 [जावास्क्रिप्ट में निष्पादन संदर्भ, उत्थान, स्कोप्स, और क्लोजर के लिए अंतिम गाइड — टायलर मैकगिनीस](https://www.youtube.com/watch?v=Nt-qa_LlUH0)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 2. Primitive Types

### सामग्री

 * 📜 [कैसे संख्या जावास्क्रिप्ट में एन्कोड किया गया है — डॉ एक्सेल रौशमेयर](http://2ality.com/2012/04/number-encoding.html)
 * 📜 [जावास्क्रिप्ट नंबर प्रकार के बारे में आपको क्या पता होना चाहिए - मैक्स विज़ार्ड के](https://medium.com/dailyjs/javascripts-number-type-8d59199db1b6)
 * 📜 [प्रत्येक जावास्क्रिप्ट डेवलपर को फ़्लोटिंग पॉइंट नंबरों के बारे में क्या पता होना चाहिए - चवक्सय](https://blog.chewxy.com/2014/02/24/what-every-javascript-developer-should-know-about-floating-point-numbers/)
 * 📜 [जावास्क्रिप्ट प्राइमेटिव्स का गुप्त जीवन - एंगस क्रॉल](https://javascriptweblog.wordpress.com/2010/09/27/the-secret-life-of-javascript-primitives/)
 * 📜 [आदिम प्रकार - प्रवाह](https://flow.org/en/docs/types/primitives/)
 * 📜 [(नहीं) जावास्क्रिप्ट में सब कुछ एक वस्तु है - डैनियल ली](http://blog.brew.com.hk/not-everything-in-javascript-is-an-object/)
 * 📜 [जावास्क्रिप्ट डेटा प्रकार और डेटा संरचनाएं - एमडीएन](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Data_structures#Primitive_values)

### Videos

 * 🎥 [जावास्क्रिप्ट संदर्भ बनाम आदिम प्रकार - अकादमिक](https://www.youtube.com/watch?v=9ooYYRLdg_g)
 * 🎥 [जावास्क्रिप्ट आदिम प्रकार - साइमन सेज़ आईटी](https://www.youtube.com/watch?v=HsbWQsSCE5Y)
 * 🎥 [जावास्क्रिप्ट में मूल्य प्रकार और संदर्भ प्रकार - मोश के साथ प्रोग्रामिंग](https://www.youtube.com/watch?v=e-_mDyqm2oU)
 * 🎥 [जावास्क्रिप्ट आदिम डेटा प्रकार - एवलक्स](https://www.youtube.com/watch?v=qw3j0A3DIzQ)
 * 🎥 [सबकुछ जो आप जावास्क्रिप्ट नंबरों के बारे में कभी नहीं जानना चाहते थे - बार्टक स्ज़ोपका](https://www.youtube.com/watch?v=MqHDDtVYJRI)
 * 🎥 [जावास्क्रिप्ट में चर क्या हैं? - सभी के लिए जेएस](https://www.youtube.com/watch?v=B4Bbmei_thw)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 3. मूल्य प्रकार और संदर्भ प्रकार

### सामग्री

 * 📜 [जावास्क्रिप्ट में मूल्य बनाम संदर्भ समझाएं - अर्नाव अग्रवाल](https://codeburst.io/explaining-value-vs-reference-in-javascript-647a975e12a0)
 * 📜 [जावास्क्रिप्ट में मूल्य और संदर्भ प्रकार को समझें - ज़ोल्ल्ट नागी](https://www.zsoltnagy.eu/understand-value-and-reference-types-in-javascript/)
 * 📜 [जावास्क्रिप्ट में आदिम प्रकार और संदर्भ प्रकार - ब्रान वैन डेर मीर](https://gist.github.com/branneman/7fb06d8a74d7e6d4cbcf75c50fec599c)
 * 📜 [जावास्क्रिप्ट में मूल्य प्रकार, संदर्भ प्रकार और दायरा - बेन एस्टन](https://medium.com/@benastontweet/lesson-1b-javascript-fundamentals-380f601ba851)
 * 📜 [जड़ों पर वापस: जावास्क्रिप्ट वैल्यू बनाम संदर्भ - मिरो कोक्ज़ा](https://medium.com/dailyjs/back-to-roots-javascript-value-vs-reference-8fb69d587a18)
 * 📜 [जावास्क्रिप्ट में "मूल्य से" और "संदर्भ द्वारा" समझें - लेना फॉरेर](https://hackernoon.com/grasp-by-value-and-by-reference-in-javascript-7ed75efa1293)
 * 📜 [जावास्क्रिप्ट संदर्भ और प्रतिलिपि चर - विटर कैपरेज़](https://hackernoon.com/javascript-reference-and-copy-variables-b0103074fdf0)
 * 📜 [जावास्क्रिप्ट आदिम बनाम संदर्भ मान](http://www.javascripttutorial.net/javascript-primitive-vs-reference-values/)
 * 📜 [संदर्भ बनाम मूल्य द्वारा जावास्क्रिप्ट - नबिनिनोवित्ज़](https://stackoverflow.com/questions/6605640/javascript-by-reference-vs-by-value)

### वीडियो

 * 🎥 [जावास्क्रिप्ट पास वैल्यू बनाम पास द्वारा संदर्भ - टेकसिथ](https://www.youtube.com/watch?v=E-dAnFdq8k8)
 * 🎥 [जावास्क्रिप्ट वैल्यू बनाम संदर्भ प्रकार - मोश के साथ प्रोग्रामिंग](https://www.youtube.com/watch?v=fD0t_DKREbE)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 4. लागू, स्पष्ट, नाममात्र, संरचनात्मक और बतख टाइपिंग

### सामग्री

 * 📜 [आपको जावास्क्रिप्ट के लागू जबरन के बारे में क्या जानने की आवश्यकता है - वादा टोची](https://dev.to/promhize/what-you-need-to-know-about-javascripts-implicit-coercion-e23)
 * 📜 [जावास्क्रिप्ट प्रकार जबरन समझाया - एलेक्सी सामोशकिन](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839)
 * 📜 [जावास्क्रिप्ट जबरन समझाया गया - बेन गैरीसन जावास्क्रिप्ट जबरन समझाया - बेन गैरीसन](https://hackernoon.com/javascript-coercion-explained-545c895213d3)
 * 📜 [जावास्क्रिप्ट में टाइप जबरदस्ती क्या है? - स्टैक ओवरफ़्लो](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript)
 * 📜 [आप जेएस नहीं जानते: प्रकार और व्याकरण [पुस्तक] - केली सिम्पसन](https://www.oreilly.com/library/view/you-dont-know/9781491905159/ch04.html)
 * 📜 [(नहीं) जावास्क्रिप्ट में सब कुछ एक वस्तु है - डैनियल ली](http://blog.brew.com.hk/not-everything-in-javascript-is-an-object/)
 * 📜 [जावास्क्रिप्ट में जबरदस्ती टाइप करें, और क्यों हर कोई इसे गलत मानता है।](https://thedevs.network/blog/type-coercion-in-javascript-and-why-everyone-gets-it-wrong)

 ### वीडियो

 * 🎥 [== ? === ??? ...#@^% - शर्मंग बीलेफेल्ड](https://www.youtube.com/watch?v=qGyqzN0bjhc&t)
 * 🎥 [जावास्क्रिप्ट में अंतर्निहित रूपांतरण - हितेश चौधरी](https://www.youtube.com/watch?v=b04Q_vyqEG8)
 * 🎥 [जावास्क्रिप्ट प्रश्न: निहित रूपांतरण क्या है? स्टीवन हैंकॉक](https://www.youtube.com/watch?v=z4-8wMSPJyI)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 5. == vs === vs typeof

### Articles

 * 📜 [जावास्क्रिप्ट डबल बराबर बनाम ट्रिपल बराबर - ब्रैंडन मोरेली](https://codeburst.io/javascript-double-equals-vs-triple-equals-61d4ce5a121a)
 * 📜 [जेएस में =, ==, और === के बीच क्या अंतर है? - कोडेकैडी](https://www.codecademy.com/en/forum_questions/558ea4f5e39efed371000508)
 * 📜 [क्या मुझे जावास्क्रिप्ट में === या == समानता तुलना ऑपरेटर का उपयोग करना चाहिए? - पनु पिटककाकी](https://bytearcher.com/articles/equality-comparison-operator-javascript/)
 * 📜 [== बनाम === जावास्क्रिप्ट: डबल बराबर और जबरन - एजे मेघानी](https://www.codementor.io/javascript/tutorial/double-equals-and-coercion-in-javascript)
 * 📜 [जावास्क्रिप्ट में ट्रिपल-बराबर ऑपरेटर का उपयोग क्यों करें? - लुई लाज़रिस](https://www.impressivewebs.com/why-use-triple-equals-javascipt/)
 * 📜 [जावास्क्रिप्ट में == और === के बीच क्या अंतर है? क्रेग बकलर](https://www.oreilly.com/learning/what-is-the-difference-between-and-in-javascript)
 * 📜 [क्यों जावास्क्रिप्ट का टाइप हमेशा "ऑब्जेक्ट" लौटाता है? - स्टैक ओवरफ़्लो](https://stackoverflow.com/questions/3787901/why-javascripts-typeof-always-return-object)
 * 📜 [जावास्क्रिप्ट में प्रकार की जांच - टोबी हो](http://tobyho.com/2011/01/28/checking-types-in-javascript/)
 * 📜 [जावास्क्रिप्ट में डेटा प्रकारों को बेहतर तरीके से कैसे जांचें - वेबबॉक](https://webbjocke.com/javascript-check-data-types/)
 * 📜 [जावास्क्रिप्ट में एक मूल्य की अनुपस्थिति की जांच - टॉमर एबरबैक](https://tomeraberba.ch/html/post/checking-for-the-absence-of-a-value-in-javascript.html)

### वीडियो

 * 🎥 [जावास्क्रिप्ट - टाइपफ ऑपरेटर - जावा दिमाग](https://www.youtube.com/watch?v=ol_su88I3kw)
 * 🎥 [जावास्क्रिप्ट टाइपोफ ऑपरेटर - देवडेलाइट](https://www.youtube.com/watch?v=qPYhTPt_SbQ)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 6. फंक्शन स्कोप, ब्लॉक स्कोप और लेक्सिकल स्कोप

### सामग्री

 * 📜 [आप जेएस नहीं जानते: स्कोप और क्लोजर [पुस्तक] - केली सिम्पसन](https://github.com/getify/You-Dont-Know-JS/blob/master/scope%20%26%20closures/ch3.md)
 * 📜 [जावास्क्रिप्ट कार्यों - मूल बातें समझना - ब्रैंडन मोरेली](https://codeburst.io/javascript-functions-understanding-the-basics-207dbf42ed99)
 * 📜 [फंक्शन स्कोप और ब्लॉक स्कोप के बीच लड़ाई - मारियस हेरिंग](http://www.deadcoderising.com/2017-04-11-es6-var-let-and-const-the-battle-between-function-scope-and-block-scope/)
 * 📜 [जावास्क्रिप्ट में नकल ब्लॉक स्कोप - जोश क्लैंटन](http://adripofjavascript.com/blog/drips/emulating-block-scope-in-javascript.html)
 * 📜 [जावास्क्रिप्ट में फंक्शन और ब्लॉक स्कोप के बीच का अंतर - जोसेफ कार्डिलो](https://medium.com/@josephcardillo/the-difference-between-function-and-block-scope-in-javascript-4296b2322abe)
 * 📜 [जावास्क्रिप्ट में फ़ंक्शन स्कोप्स और ब्लॉक स्कोप्स - समर बुना](https://edgecoders.com/function-scopes-and-block-scopes-in-javascript-25bbd7f293d7)
 * 📜 [जावास्क्रिप्ट में स्कोप और संदर्भ को समझना | रयान मोर](http://ryanmorr.com/understanding-scope-and-context-in-javascript/)
 * 📜 [जावास्क्रिप्ट स्कोप और क्लोजर - ज़ेल लियू](https://css-tricks.com/javascript-scope-closures/)
 * 📜 [जावास्क्रिप्ट में स्कोप को समझना - विस्मत अबीरचेड](https://developer.telerik.com/topics/web-development/understanding-scope-in-javascript/)
 * 📜 [जावास्क्रिप्ट बोलना - चर: स्कोप्स, वातावरण, और बंद - डॉ एक्सेल रौशमेयर](http://speakingjs.com/es5/ch16.html)
 * 📜 [जावास्क्रिप्ट में स्कोप को समझना - हम्माद अहमद](https://scotch.io/tutorials/understanding-scope-in-javascript)

### वीडियो

 * 🎥 [क्या जावास्क्रिप्ट अजीब बनाता है ... और बहुत बढ़िया pt. 4 - LearnCode.academy](https://www.youtube.com/watch?v=SBwoFkRjZvE)
 * 🎥 [जावास्क्रिप्ट में परिवर्तनीय दायरा - किरुपा चिन्नाथंबी](https://www.youtube.com/watch?v=dhp57T3p760)
 * 🎥 [जावास्क्रिप्ट ब्लॉक स्कोप और फ़ंक्शन स्कोप - mmtuts](https://www.youtube.com/watch?v=aK_nuUAdr8E)
 * 🎥 [हेक्स लेक्सिकल स्कोप क्या है? - एनडब्ल्यू कैलवान](https://www.youtube.com/watch?v=GhNA0r10MmA)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 7. अभिव्यक्ति बनाम वक्तव्य

### सामग्री

 * 📜 [आपको जावास्क्रिप्ट के अभिव्यक्तियों, वक्तव्यों और अभिव्यक्ति वक्तव्यों के बारे में जानने की आवश्यकता है - वादा टोची](https://dev.to/promhize/javascript-in-depth-all-you-need-to-know-about-expressions-statements-and-expression-statements-5k2)
 * 📜 [समारोह अभिव्यक्ति बनाम समारोह घोषणा - पॉल विल्किन्स](https://www.sitepoint.com/function-expressions-vs-declarations/)
 * 📜 [जावास्क्रिप्ट फ़ंक्शन - घोषणा बनाम अभिव्यक्ति - रवि रोशन](https://medium.com/@raviroshan.talk/javascript-function-declaration-vs-expression-f5873b8c7b38)
 * 📜 [फंक्शन घोषणा बनाम फंक्शन एक्सप्रेशन - मनदीप सिंह](https://medium.com/@mandeep1012/function-declarations-vs-function-expressions-b43646042052)
 * 📜 [फंक्शन घोषणा बनाम फंक्शन एक्सप्रेशन - एंगल्स क्रॉल](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)

### वीडियो

 * 🎥 [जावास्क्रिप्ट में अभिव्यक्ति बनाम विवरण - हेक्सलेट](https://www.youtube.com/watch?v=WVyCrI1cHi8)
 * 🎥 [जावास्क्रिप्ट - अभिव्यक्ति बनाम वक्तव्य - वेब ट्यूनिंग्स](https://www.youtube.com/watch?v=3jDpNGJkupA)
 * 🎥 [फंक्शन स्टेटमेंट्स एंड फंक्शन एक्सप्रेशन - कोडेकैडमी](https://www.youtube.com/watch?v=oB5rH_9bqAI)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 8. आईआईएफई, मॉड्यूल और नेमस्पेस

### सामग्री

 * 📜 [मास्टरिंग तत्काल-आमंत्रित समारोह अभिव्यक्ति - चंद्र गुंडमारजू](https://medium.com/@vvkchandra/essential-javascript-mastering-immediately-invoked-function-expressions-67791338ddc6)
 * 📜 [क्या ईएस 6 मॉड्यूल आईआईएफई अप्रचलित होने का मामला बनाते हैं?](https://hashnode.com/post/do-es6-modules-make-the-case-of-iifes-obsolete-civ96wet80scqgc538un20es0)
 * 📜 [जावास्क्रिप्ट मॉड्यूल, मॉड्यूल प्रारूप, मॉड्यूल लोडर और मॉड्यूल बंडलर के लिए एक 10 मिनट प्राइमर - जुर्गन वान डी मोरे](https://www.jvandemo.com/a-10-minute-primer-to-javascript-modules-module-formats-module-loaders-and-module-bundlers/)
 * 📜 [मॉड्यूल - जेएस की खोज](http://exploringjs.com/es6/ch_modules.html)
 * 📜 [ईएस मॉड्यूल: एक कार्टून गहरे गोताखोर - लिन क्लार्क](https://hacks.mozilla.org/2018/03/es-modules-a-cartoon-deep-dive/)
 * 📜 [ES6 मॉड्यूल को समझना - क्रेग बकलर](https://www.sitepoint.com/understanding-es6-modules/)
 * 📜 [जावास्क्रिप्ट में ईएस 6 मॉड्यूल का एक सिंहावलोकन - ब्रेंट ग्राहम](https://blog.cloud66.com/an-overview-of-es6-modules-in-javascript/)
 * 📜 [गहराई में ES6 मॉड्यूल - निकोलस बेवाक्वा](https://ponyfoo.com/articles/es6-modules-in-depth)
 * 📜 [ईएस 6 मॉड्यूल, नोड.जेएस और माइकल जैक्सन समाधान - अल्बर्टो गिमेनो](https://medium.com/dailyjs/es6-modules-node-js-and-the-michael-jackson-solution-828dc244b8b)
 * 📜 [जावास्क्रिप्ट मॉड्यूल: एक शुरुआती गाइड - प्रीती कासेरेड्डी](https://medium.freecodecamp.org/javascript-modules-a-beginner-s-guide-783f7d7a5fcc)

### वीडियो

 * 🎥 [तुरंत आमंत्रित फोकस अभिव्यक्ति - Beau जावास्क्रिप्ट सिखाता है - freeCodeCamp](https://www.youtube.com/watch?v=3cbiZV4H22c)
 * 🎥 [जावास्क्रिप्ट आईआईएफई को समझना](https://www.youtube.com/watch?v=I5EntfMeIIQ)
 * 🎥 [जावास्क्रिप्ट मॉड्यूल: ईएस 6 आयात और निर्यात - केली रॉबिन्सन](https://www.youtube.com/watch?v=_3oSWwapPKQ)
 * 🎥 [ईएस 6 - मॉड्यूल - रयान क्रिस्टियन](https://www.youtube.com/watch?v=aQr2bV1BPyE)
 * 🎥 [रियल वर्ल्ड में ईएस 6 मॉड्यूल - सैम थोरोगूड](https://www.youtube.com/watch?v=fIP4pjAqCtQ)
 * 🎥 [ईएस 6 मॉड्यूल - टेम्पलकोडिंग](https://www.youtube.com/watch?v=5P04OK6KlXA)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 9. संदेश कतार और घटना लूप

### सामग्री

 * 📜 [जावास्क्रिप्ट इवेंट लूप समझाया - Anoop Raveendran](https://medium.com/front-end-hacking/javascript-event-loop-explained-4cd26af121d4)
 * 📜 [जावास्क्रिप्ट इवेंट लूप: समझाया गया - एरिन स्वसन-हेली](https://blog.carbonfive.com/2013/10/27/the-javascript-event-loop-explained/)
 * 📜 [जावास्क्रिप्ट में इवेंट लूप क्या है - WP Tutor.io](https://www.wptutor.io/web/js/javascript-event-loop)
 * 📜 [जेएस को समझना: इवेंट लूप - अलेक्जेंडर कोंडोव](https://hackernoon.com/understanding-js-the-event-loop-959beae3ac40)
 * 📜 [जावास्क्रिप्ट इवेंट लूप को समझना - आशीष गुप्ता](https://www.zeolearn.com/magazine/understanding-the-javascript-event-loop)
 * 📜 [जावास्क्रिप्ट में इवेंट लूप - मंजुला ड्यूब](https://code.likeagirl.io/what-the-heck-is-event-loop-1e414fccef49)
 * 📜 [जावास्क्रिप्ट इवेंट लूप - फ्लैवियो कॉप्स](https://flaviocopes.com/javascript-event-loop/)
 * 📜 [जावास्क्रिप्ट कैसे काम करता है: इवेंट लूप - अलेक्जेंडर ज़्लाटकोव](https://blog.sessionstack.com/how-javascript-works-event-loop-and-the-rise-of-async-programming-5-ways-to-better-coding-with-2f077c4438b5)
 * 📜 [एक पिज्जा रेस्तरां समानता के साथ जावास्क्रिप्ट इवेंट लूप को विज़ुअलाइज करना - प्रियंश जैन](https://dev.to/presto412/visualising-the-javascript-event-loop-with-a-pizza-restaurant-analogy-47a8)

### वीडियो

 * 🎥 [वैसे भी घटना लूप क्या बिल्ली है? | जेएससीओएनएफ ईयू - फिलिप रॉबर्ट्स](https://www.youtube.com/watch?v=8aGhZQkoFbQ)
 * 🎥 [जावास्क्रिप्ट इवेंट लूप - कॉमसाइंस सरलीकृत](https://www.youtube.com/watch?v=XzXIMZMN9k4)
 * 🎥 [मैं एक घटना लूप में फंस गया हूँ - फिलिप रॉबर्ट्स](https://www.youtube.com/watch?v=6MXRNXXgP_0)
 * 🎥 [लूप में - जेक आर्किबाल्ड | जेएससीओएनएफ.एशिया 2018](https://www.youtube.com/watch?v=cCOL7MC4Pl0)
 * 🎥 [Desmitificando एल इवेंट लूप (स्पेनिश)](https://www.youtube.com/watch?v=Eqq2Rb7LzYE)


**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 10. setTimeout, setInterval और requestAnimationFrame

### सामग्री

 * 📜 [सेटटाइमआउट और सेट इंटरवल - जावास्क्रिप्ट.इन्फो](https://javascript.info/settimeout-setinterval)
 * 📜 [सेट इंटरवल का उपयोग क्यों न करें - अखंड शर्मा](https://dev.to/akanksha_9560/why-not-to-use-setinterval--2na9)
 * 📜 [सेटटाइमआउट VS सेट इंटरवल - डेवेलोगर](https://develoger.com/settimeout-vs-setinterval-cff85142555b)
 * 📜 [अनुरोध का उपयोग एनीमेशन फ्रेम - क्रिस कोयियर](https://css-tricks.com/using-requestanimationframe/)
 * 📜 [जावास्क्रिप्ट के अनुरोध को समझनाएनीमेशन फ्रेम () - जावास्क्रिप्ट किट](http://www.javascriptkit.com/javatutors/requestanimationframe.shtml)
 * 📜 [जावास्क्रिप्ट में समय अंतराल को संभालना - अमित व्यापारी](https://www.amitmerchant.com/Handling-Time-Intervals-In-Javascript/)

### वीडियो

 * 🎥 [जावास्क्रिप्ट: कैसे सेटटाइमआउट और सेट इंटरवल काम करता है - कोडिंग ब्लॉक भारत](https://www.youtube.com/watch?v=6bPKyl8WYWI)
 * 🎥 [जावास्क्रिप्ट में setTimeout और setInterval - techsith](https://www.youtube.com/watch?v=TbCgGWe8LN8)
 * 🎥 [जावास्क्रिप्ट टाइमर - स्टीव ग्रिफिथ](https://www.youtube.com/watch?v=0VVJSvlUgtg)
 * 🎥 [जावास्क्रिप्ट सेटटाइमआउट, सेट इंटरवल और स्पष्ट अंतराल - DoingITeasyChannel](https://www.youtube.com/watch?v=BVALvvy5bZY)
 * 🎥 [जावास्क्रिप्ट सेटटाइमऑट और सेट इंटरवल समझाया - थियोडोर एंडरसन](https://www.youtube.com/watch?v=mVKfrWCOB60)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 11. जावास्क्रिप्ट इंजन

### सामग्री

 * 📜 [जावास्क्रिप्ट इंजन - जेन लूपर](http://www.softwaremag.com/javascript-engines/)
 * 📜 [यह समझना कि क्रोम वी 8 इंजन जावास्क्रिप्ट को मशीन कोड में कैसे अनुवादित करता है - DroidHead](https://medium.freecodecamp.org/understanding-the-core-of-nodejs-the-powerful-chrome-v8-engine-79e7eb8af964)
 * 📜 [वी 8 के बाइटकोड को समझना - फ्रांजिसका हिंकेलमैन](https://medium.com/dailyjs/understanding-v8s-bytecode-317d46c94775)
 * 📜 [वी 8 इंजन कैसे काम करता है? - थिबॉल्ट लॉरेन](http://thibaultlaurens.github.io/javascript/2013/04/29/how-the-v8-engine-works/)
 * 📜 [Google के वी 8 जावास्क्रिप्ट इंजन का एक संक्षिप्त इतिहास - क्लेयर स्मिथ](https://www.mediacurrent.com/blog/brief-history-googles-v8-javascript-engine/)
 * 📜 [जावास्क्रिप्ट आवश्यक: आपको क्यों पता होना चाहिए कि इंजन कैसे काम करता है - रेनर हैनकेम्प](https://medium.freecodecamp.org/javascript-essentials-why-you-should-know-how-the-engine-works-c2cc0d321553)


### वीडियो

 * 🎥 [जावास्क्रिप्ट इंजन: गुड पार्ट्स ™ - माथीस बायेंस और बेनेडिक्ट मेयूर](https://www.youtube.com/watch?v=5nmpokoRaZI)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 12. बिटवाई ऑपरेटर, टाइप एरे और ऐरे बफर

### सामग्री

 * 📜 [जेएस के साथ प्रोग्रामिंग: बिटवाई ऑपरेशंस - अलेक्जेंडर कोंडोव](https://hackernoon.com/programming-with-js-bitwise-operations-393eb0745dc4)
 * 📜 [रीयल लाइफ में जावास्क्रिप्ट के बिटवाईयर ऑपरेटरों का उपयोग करना - इयान एम](https://codeburst.io/using-javascript-bitwise-operators-in-real-life-f551a731ff5)
 * 📜 [जावास्क्रिप्ट बिटवाई ऑपरेटर्स - w3resource](https://www.w3resource.com/javascript/operators/bitwise-operator.php)
 * 📜 [जावास्क्रिप्ट में बिटवाई ऑपरेटर - जो चा](https://medium.com/bother7-blog/bitwise-operators-in-javascript-65c4c69be0d3)
 * 📜 [जावास्क्रिप्ट में बाइनरी गणना और बिटवाई ऑपरेटरों पर एक व्यापक प्राइमर - पॉल ब्राउन](https://medium.com/techtrument/a-comprehensive-primer-on-binary-computation-and-bitwise-operators-in-javascript-81acf8341f04)

 ### वीडियो

 * 🎥 [जावास्क्रिप्ट बिटवे ऑपरेटर्स - मोश के साथ प्रोग्रामिंग](https://www.youtube.com/watch?v=mesu75PTDC8)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 13. डोम और लेआउट पेड़

### सामग्री

 * 📜 [जावास्क्रिप्ट में डोम को कैसे समझें और संशोधित करें - तानिया रसिया](https://www.digitalocean.com/community/tutorials/introduction-to-the-dom)
 * 📜 [दस्तावेज़ ऑब्जेक्ट मॉडल क्या है, और आपको इसका उपयोग क्यों करना चाहिए - लियोनार्डो मालडोनाडो](https://medium.freecodecamp.org/whats-the-document-object-model-and-why-you-should-know-how-to-use-it-1a2d0bc5429d)
 * 📜 [उदाहरण के साथ जावास्क्रिप्ट डोम ट्यूटोरियल - गुरु 99](https://www.guru99.com/how-to-use-dom-and-events-in-javascript.html)
 * 📜 [डोम क्या है? - क्रिस कोयियर](https://css-tricks.com/dom/)
 * 📜 [जावास्क्रिप्ट के साथ डोम ट्रैवर्सिंग - ज़ेल लिव](https://zellwk.com/blog/dom-traversals/)
 * 📜 [वांछित जावास्क्रिप्ट [पुस्तक] - दस्तावेज़ ऑब्जेक्ट मॉडल](https://eloquentjavascript.net/14_dom.html)
 * 📜 [डोम ट्री](https://javascript.info/dom-nodes)
 * 📜 [जावास्क्रिप्ट में डोम को कैसे पार करें - Vojislav Grujić](https://medium.com/javascript-in-plain-english/how-to-traverse-the-dom-in-javascript-d6555c335b4e)
 * 📜 [रेंडर ट्री कंस्ट्रक्शन - इलिया ग्रिगोरिक](https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-tree-construction)

 ### वीडियो

 * 🎥 [जावास्क्रिप्ट डोम - नेट निंजा](https://www.youtube.com/watch?v=FIORjGvT0kk)
 * 🎥 [जावास्क्रिप्ट डोम क्रैश कोर्स - ट्रैवर्स मीडिया](https://www.youtube.com/watch?v=0ik6X4DJKCc)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 14. कारखानों और वर्गों

### सामग्री

 * 📜 [जावास्क्रिप्ट में कक्षाओं का उपयोग कैसे करें - तानिया रसिया](https://www.digitalocean.com/community/tutorials/understanding-classes-in-javascript)
 * 📜 [जावास्क्रिप्ट क्लासेस - हूड के तहत - मजीद](https://medium.com/tech-tajawal/javascript-classes-under-the-hood-6b26d2667677)
 * 📜 [ईएस 6 कक्षाएं - नथनील फोस्टर](https://www.javascriptjanuary.com/blog/es6-classes)
 * 📜 [ईएस 6, पीटी के साथ बेहतर जावास्क्रिप्ट। II: कक्षाओं में एक गहरी गोता - Peleke Sengstacke](https://scotch.io/tutorials/better-javascript-with-es6-pt-ii-a-deep-dive-into-classes)
 * 📜 [सादा जावास्क्रिप्ट में फैक्टरी डिजाइन पैटर्न को समझें - आदित्य अग्रवाल](https://medium.com/front-end-hacking/understand-the-factory-design-pattern-in-plain-javascript-20b348c832bd)
 * 📜 [जावास्क्रिप्ट में फैक्टरी कार्य - जोश मिलर](https://atendesigngroup.com/blog/factory-functions-javascript)
 * 📜 [जेएस ES6 में फैक्टरी पैटर्न - SnstsDev](https://medium.com/@SntsDev/the-factory-pattern-in-js-es6-78f0afad17e9)
 * 📜 [क्लास बनाम फैक्टरी फ़ंक्शन: आगे बढ़ने के तरीके की खोज - क्रिस्टी साल्सेस्कु](https://medium.freecodecamp.org/class-vs-factory-function-exploring-the-way-forward-73258b6a8d15)
 * 📜 [ईएस 6 कक्षाएं वास्तव में कैसे काम करती हैं और अपना खुद का निर्माण कैसे करें - रॉबर्ट ग्रोस](https://medium.com/@robertgrosse/how-es6-classes-really-work-and-how-to-build-your-own-fd6085eb326a)

 ### वीडियो

 * 🎥 [जावास्क्रिप्ट फैक्टरी कार्य - मोश के साथ प्रोग्रामिंग](https://www.youtube.com/watch?v=jpegXpQpb3o)
 * 🎥 [जावास्क्रिप्ट में फैक्टरी कार्य - मज़ा मज़ा समारोह](https://www.youtube.com/watch?v=ImwrezYhw4w)
 * 🎥 [जावास्क्रिप्ट ट्यूटोरियल फ़ंक्शन फैक्ट्रीज़ - क्रिप्टो चैन](https://www.youtube.com/watch?v=R7-IwpH80UE)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 15. यह, कॉल, आवेदन और बाध्य

### सामग्री

 * 📜 [कैसे करें: कॉल (), जावास्क्रिप्ट में लागू () और बाइंड () - निलाद्री सेखर दत्ता](https://www.codementor.io/niladrisekhardutta/how-to-call-apply-and-bind-in-javascript-8i1jca6jp)
 * 📜 [जावास्क्रिप्ट के लागू, कॉल, और बाइंड विधि जावास्क्रिप्ट पेशेवरों के लिए आवश्यक हैं - रिचर्ड बोवेल](http://javascriptissexy.com/javascript-apply-call-and-bind-methods-are-essential-for-javascript-professionals/)
 * 📜 [डब्ल्यूटीएफ यह है - इस कीवर्ड को समझना, जावास्क्रिप्ट में कॉल करें, लागू करें और बाध्य करें - टायलर मैकगिनीस](https://tylermcginnis.com/this-keyword-call-apply-bind-javascript/)
 * 📜 [जावास्क्रिप्ट: कॉल (), लागू करें () और बाइंड () - ओमर गोल्डबर्ग](https://medium.com/@omergoldberg/javascript-call-apply-and-bind-e5c27301f7bb)
 * 📜 [कॉल / लागू / बाइंड - इवान सिफ्रिम के बीच का अंतर](https://medium.com/@ivansifrim/the-differences-between-call-apply-bind-276724bb825b)
 * 📜 [कॉल (), जावास्क्रिप्ट में लागू () और बाइंड () विधियों](https://tech.io/playgrounds/9799/learn-solve-call-apply-and-bind-methods-in-javascript)
 * 📜 [जावास्क्रिप्ट में 'यह' मास्टरिंग: कॉलबैक और बाइंड (), लागू करें (), कॉल () - मिशेल गिएनो](https://thenewstack.io/mastering-javascript-callbacks-bind-apply-call/)
 * 📜 [JavaScript’s apply, call, and bind explained by hosting a cookout — Kevin Kononenko](https://dev.to/kbk0125/javascripts-apply-call-and-bind-explained-by-hosting-a-cookout-32jo)
 * 📜 [कैसे और कब बाध्य, कॉल, और जावास्क्रिप्ट में लागू करने के लिए - Eigen एक्स](https://www.eigenx.com/blog/https/mediumcom/eigen-x/how-and-when-to-use-bind-call-and-apply-in-javascript-77b6f42898fb)
 * 📜 [जावास्क्रिप्ट। बाइंड () बनाम .apply () और .call () - हैक स्पैरो](https://www.hacksparrow.com/javascript-bind-vs-apply-and-call.html)
 * 📜 [कॉल () - एमडीएन](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/call)
 * 📜 [बांध () - एमडीएन](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_objects/Function/bind)
 * 📜 [आवेदन करें () - एमडीएन](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/apply)
 * 📜 [जावास्क्रिप्ट में 'यह' क्या है? - डैनियल ली](http://blog.brew.com.hk/what-is-this-in-javascript/)
 * 📜 [मैं आपको बताता हूं कि यह 'क्या है'। (जावास्क्रिप्ट) - जेसन यू](https://dev.to/ycmjason/let-me-explain-to-you-what-is-this-javascript-44ja)
 * 📜 [जावास्क्रिप्ट में "यह" कीवर्ड को समझना - पवन](https://medium.com/quick-code/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)

  ### वीडियो

 * 🎥 [जावास्क्रिप्ट कॉल, लागू करें और बाध्य - techsith](https://www.youtube.com/watch?v=c0mLRpw-9rI)
 * 🎥 [जावास्क्रिप्ट प्रैक्टिकल एप्लीकेशन कॉल, लागू करें और बाइंड फ़ंक्शन- techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)
 * 🎥 [जावास्क्रिप्ट (कॉल, बाइंड, लागू) — curious aatma](https://www.youtube.com/watch?v=Uy0NOXLBraE)
 * 🎥 [ईएस2017 की दुनिया में कार्यों को समझना और 'यह' - ब्रायन ह्यूजेस](https://www.youtube.com/watch?v=AOSYY1_np_4)
 * 🎥 [बाध्य और यह - जावास्क्रिप्ट में ऑब्जेक्ट क्रिएशन - FunFunFunction](https://www.youtube.com/watch?v=GhbhD1HR5vk)
 * 🎥 [कॉल, लागू करें और बाध्य कार्यों के जावास्क्रिप्ट प्रैक्टिकल एप्लीकेशन — techsith](https://www.youtube.com/watch?v=AYVYxezrMWA)
 * 🎥 [जेएस फंक्शन विधि कॉल (), लागू (), और बाइंड () - स्टीव ग्रिफिथ](https://www.youtube.com/watch?v=uBdH0iB1VDM)
 
**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 16. new, Constructor, instanceof and Instances

### Articles

 * 📜 [JavaScript For Beginners: the ‘new’ operator — Brandon Morelli](https://codeburst.io/javascript-for-beginners-the-new-operator-cee35beb669e)
 * 📜 [Let’s demystify JavaScript’s ‘new’ keyword — Cynthia Lee](https://medium.freecodecamp.org/demystifying-javascripts-new-keyword-874df126184c)
 * 📜 [Constructor, operator "new" — JavaScript.Info](https://javascript.info/constructor-new)
 * 📜 [Understanding JavaScript Constructors — Faraz Kelhini](https://css-tricks.com/understanding-javascript-constructors/)
 * 📜 [Use Constructor Functions — Openclassrooms](https://openclassrooms.com/en/courses/3523231-learn-to-code-with-javascript/4379006-use-constructor-functions)
 * 📜 [Beyond `typeof` and `instanceof`: simplifying dynamic type checks — Dr. Axel Rauschmayer](http://2ality.com/2017/08/type-right.html)
 * 📜 [What Is the Instanceof Operator in JavaScript — appendTo](https://appendto.com/2016/10/what-is-the-instanceof-operator-in-javascript/)
 * 📜 [JavaScript instanceof vs typeof — Gary Rafferty](http://garyrafferty.com/2012/12/07/JavaScript-instanceof-vs-typeof.html)
 * 📜 [Function and Object, instances of each other — Kiro Risk](https://javascriptrefined.io/function-and-object-instances-of-each-other-1e1095d5faac)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 17. Prototype Inheritance and Prototype Chain

### Articles

 * 📜 [Javascript : Prototype vs Class — Valentin PARSY](https://medium.com/@parsyval/javascript-prototype-vs-class-a7015d5473b)
 * 📜 [JavaScript engine fundamentals: optimizing prototypes — Mathias Bynens](https://mathiasbynens.be/notes/prototypes)
 * 📜 [JavaScript Prototype — NC Patro](https://codeburst.io/javascript-prototype-cb29d82b8809)
 * 📜 [Prototype in Javascript — Sandeep Ranjan](https://www.codementor.io/sandeepranjan2007/prototype-in-javascipt-knbve0lqo)
 * 📜 [Prototypes in JavaScript — Rupesh Mishra](https://hackernoon.com/prototypes-in-javascript-5bba2990e04b)
 * 📜 [Prototype in JavaScript: it’s quirky, but here’s how it works — Pranav Jindal](https://medium.freecodecamp.org/prototype-in-js-busted-5547ec68872)
 * 📜 [Inheritance and the prototype chain — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Inheritance_and_the_prototype_chain)
 * 📜 [Understanding JavaScript: Prototype and Inheritance — Alexander Kondov](https://hackernoon.com/understanding-javascript-prototype-and-inheritance-d55a9a23bde2)
 * 📜 [Prototypal Inheritance — JavaScript.Info](https://javascript.info/prototype-inheritance)
 * 📜 [How To Work with Prototypes and Inheritance in JavaScript — Tania Rascia](https://www.digitalocean.com/community/tutorials/understanding-prototypes-and-inheritance-in-javascript)
 * 📜 [Master JavaScript Prototypes & Inheritance — Arnav Aggarwal](https://codeburst.io/master-javascript-prototypes-inheritance-d0a9a5a75c4e)
 * 📜 [You Don't Know JS [Book] Chapter 5: Prototypes — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch5.md)
 * 📜 [JavaScript’s Prototypal Inheritance Explained Using CSS — Nash Vail](https://medium.freecodecamp.org/understanding-prototypal-inheritance-in-javascript-with-css-93b2fcda75e4)
 * 📜 [Prototypal Inheritance in JavaScript — Jannis Redmann](https://gist.github.com/derhuerst/a585c4916b1c361cc6f0)
 * 📜 [Classical and Prototypical Inheritance in JavaScript — Danny Cornelisse](http://www.competa.com/blog/classical-prototypical-inheritance-javascript/)
 * 📜 [Demystifying ES6 Classes And Prototypal Inheritance ― Neo Ighodaro](https://scotch.io/tutorials/demystifying-es6-classes-and-prototypal-inheritance)
 * 📜 [Intro To Prototypal Inheritance — Dharani Jayakanthan](https://dev.to/danny/intro-to-prototypal-inheritance---js-9di)
 * 📜 [Classes in JavaScript - Explained — Daniel Li](http://blog.brew.com.hk/classes-in-javascript-explained/)
 * 📜 [You Don't Know JS: this & Object Prototypes — Kyle Simpson](https://github.com/getify/You-Dont-Know-JS/blob/master/this%20%26%20object%20prototypes/ch4.md)

 ### Videos

 * 🎥 [Javascript Prototype Inheritance — Avelx](https://www.youtube.com/watch?v=sOrtAjyk4lQ)
 * 🎥 [JavaScript Prototype Inheritance Explained pt. I — techsith](https://www.youtube.com/watch?v=7oNWNlMrkpc)
 * 🎥 [JavaScript Prototype Inheritance Explained pt. II — techsith](https://www.youtube.com/watch?v=uIlj6_z_wL8)
 * 🎥 [JavaScript Prototype Inheritance Explained — Kyle Robinson](https://www.youtube.com/watch?v=qMO-LTOrJaE)
 * 🎥 [Advanced Javascript - Prototypal Inheritance In 1 Minute](https://www.youtube.com/watch?v=G6l5CHl67HQ)
 * 🎥 [An Overview Of Classical Javascript Classes and Prototypal Inheritance — Pentacode](https://www.youtube.com/watch?v=phwzuiJJPpQ)
 * 🎥 [Object Oriented JavaScript - Prototype — The Net Ninja](https://www.youtube.com/watch?v=4jb4AYEyhRc)
 * 🎥 [Prototype in JavaScript — kudvenkat](https://www.youtube.com/watch?v=2rkEbcptR64)
 * 🎥 [JavaScript Using Prototypes — O'Reilly](https://www.youtube.com/watch?v=oCwCcNvaXAQ)
 * 🎥 [A Beginner's Guide to Javascript's Prototype — Tyler Mcginnis](https://www.youtube.com/watch?v=XskMWBXNbp0)
 * 🎥 [Prototypes in Javascript - p5.js Tutorial — The Coding Train](https://www.youtube.com/watch?v=hS_WqkyUah8)


**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 18. Object.create and Object.assign

### Articles

 * 📜 [Object.create() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create)
 * 📜 [Object.create in JavaScript — Rupesh Mishra](https://hackernoon.com/object-create-in-javascript-fa8674df6ed2)
 * 📜 [Object.create(): the New Way to Create Objects in JavaScript — Rob Gravelle](https://www.htmlgoodies.com/beyond/javascript/object.create-the-new-way-to-create-objects-in-javascript.html)
 * 📜 [Basic Inheritance with Object.create — Joshua Clanton](http://adripofjavascript.com/blog/drips/basic-inheritance-with-object-create.html)
 * 📜 [Object.create() In JavaScript — GeeksforGeeks](https://www.geeksforgeeks.org/object-create-javascript/)
 * 📜 [Understanding the difference between Object.create() and the new operator — Jonathan Voxland](https://medium.com/@jonathanvox01/understanding-the-difference-between-object-create-and-the-new-operator-b2a2f4749358)
 * 📜 [JavaScript Object Creation: Patterns and Best Practices — Jeff Mott](https://www.sitepoint.com/javascript-object-creation-patterns-best-practises/)
 * 📜 [Dealing With Objects in JavaScript With Object.assign, Object.keys and hasOwnProperty](https://alligator.io/js/dealing-with-objects/)
 * 📜 [Copying Objects in JavaScript ― Orinami Olatunji](https://scotch.io/bar-talk/copying-objects-in-javascript)
 * 📜 [Object.assign() — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/assign)
 * 📜 [JavaScript: Object.assign() — Thiago S. Adriano](https://codeburst.io/javascript-object-assign-bc9696dcbb6e)
 * 📜 [How to deep clone a JavaScript Object — Flavio Copes](https://flaviocopes.com/how-to-clone-javascript-object/)

 ### Videos

 * 🎥 [Object.assign() explained — Aaron Writes Code](https://www.youtube.com/watch?v=aw7NfYhR5rc)
 * 🎥 [Object.assign() Method — techsith](https://www.youtube.com/watch?v=9Ky4X6inpi4)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 19. map, reduce, filter

### Articles

 * 📜 [जावास्क्रिप्ट कार्यात्मक प्रोग्रामिंग - मानचित्र, फ़िल्टर और कम करें - बोजन ग्वाज़ेडरैक](https://medium.com/jsguru/javascript-functional-programming-map-filter-and-reduce-846ff9ba492d)
 * 📜 [मानचित्र जानें, फ़िल्टर करें और जावास्क्रिप्ट में कम करें - जोआओ मिगुएल कुन्हा](https://medium.com/@joomiguelcunha/learn-map-filter-and-reduce-in-javascript-ea59009593c4)
 * 📜 [जावास्क्रिप्ट का नक्शा, घटाएं, और फ़िल्टर - डैन मार्टेंसन](https://danmartensen.svbtle.com/javascripts-map-reduce-and-filter)
 * 📜 [जावास्क्रिप्ट में मानचित्र, फ़िल्टर, और कमी का उपयोग कैसे करें - Peleke Sengstacke](https://code.tutsplus.com/tutorials/how-to-use-map-filter-reduce-in-javascript--cms-26209)
 * 📜 [जावास्क्रिप्ट - चेन मानचित्र, फ़िल्टर, और कम करने के लिए जानें - ब्रैंडन मोरेली](https://codeburst.io/javascript-learn-to-chain-map-filter-and-reduce-acd2d0562cd4)
 * 📜 [मानचित्र, कम, फ़िल्टर और ES6 - दीपक गुप्ता के साथ जावास्क्रिप्ट डेटा संरचना](https://codeburst.io/write-beautiful-javascript-with-%CE%BB-fp-es6-350cd64ab5bf)
 * 📜 [मानचित्र को समझना, जावास्क्रिप्ट में फ़िल्टर करना और कम करना - लुकू ग्रुइज](https://hackernoon.com/understanding-map-filter-and-reduce-in-javascript-5df1c7eee464)
 * 📜 [Functional Programming in JS: map, filter, reduce (Pt. 5) — Omer Goldberg](https://hackernoon.com/functional-programming-in-js-map-filter-reduce-pt-5-308a205fdd5f)
 * 📜 [JavaScript: Map, Filter, Reduce — William S. Vincent](https://wsvincent.com/functional-javascript-map-filter-reduce/)
 * 📜 [Arrow Functions: Fat and Concise Syntax in JavaScript — Kyle Pennell](https://www.sitepoint.com/es6-arrow-functions-new-fat-concise-syntax-javascript/)
 * 📜 [JavaScript: Arrow Functions for Beginners — Brandon Morelli](https://codeburst.io/javascript-arrow-functions-for-beginners-926947fc0cdc)
 * 📜 [When (and why) you should use ES6 arrow functions — and when you shouldn’t — Cynthia Lee](https://medium.freecodecamp.org/when-and-why-you-should-use-es6-arrow-functions-and-when-you-shouldnt-3d851d7f0b26)
 * 📜 [JavaScript — Learn & Understand Arrow Functions — Brandon Morelli](https://codeburst.io/javascript-learn-understand-arrow-functions-fe2083533946)
 * 📜 [(JavaScript )=> Arrow functions — sigu](https://medium.com/podiihq/javascript-arrow-functions-27d4c3334b83)
 * 📜 [A possibility to use Async/Await for filter(), find(), forEach(), map() and reduce() methods in Array — Ruwan Geeganage](https://www.linkedin.com/pulse/possibility-use-asyncawait-filter-find-foreach-map-reduce-geeganage/)
 * 📜 [Javascript.reduce() — Paul Anderson](https://medium.com/@panderson.dev/javascript-reduce-79aab078da23)
 * 📜 [Why you should replace forEach with map and filter in JavaScript — Roope Hakulinen](https://gofore.com/en/why-you-should-replace-foreach/)
 * 📜 [Simplify your JavaScript – Use .map(), .reduce(), and .filter() — Etienne Talbot](https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d)
 * 📜 [JavaScript’s Reduce Method Explained By Going On a Diet — Kevin Kononenko](https://blog.codeanalogies.com/2018/07/24/javascripts-reduce-method-explained-by-going-on-a-diet/)

 ### Videos

 * 🎥 [Map, Filter and Reduce — Lydia Hallie](https://www.youtube.com/watch?v=UXiYii0Y7Nw)
 * 🎥 [Functional JavaScript: Map, forEach, Reduce, Filter — Theodore Anderson](https://www.youtube.com/watch?v=vytzLlY_wmU)
 * 🎥 [JavaScript Array superpowers: Map, Filter, Reduce (part I) — Michael Rosata](https://www.youtube.com/watch?v=qTeeVd8hOFY)
 * 🎥 [JavaScript Array superpowers: Map, Filter, Reduce (part 2) — Michael Rosata](https://www.youtube.com/watch?v=gIm9xLYudL0)
 * 🎥 [JavaScript Higher Order Functions - Filter, Map, Sort & Reduce — Epicop](https://www.youtube.com/watch?v=zYBeEPxNSbw)
 * 🎥 [[Array Methods 2/3] .filter + .map + .reduce — CodeWithNick](https://www.youtube.com/watch?v=4qWlqD0yYTU)
 * 🎥 [Arrow functions in JavaScript - What, Why and How — Fun Fun Function](https://www.youtube.com/watch?v=6sQDTgOqh-I)
 * 🎥 [Learning Functional Programming with JavaScript — Anjana Vakil - JSUnconf](https://www.youtube.com/watch?v=e-5obm1G_FY&t=1521s)


**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 20. Pure Functions, Side Effects and State Mutation

### Articles

 * 📜 [Javascript and Functional Programming — Pure Functions — Omer Goldberg](https://hackernoon.com/javascript-and-functional-programming-pt-3-pure-functions-d572bb52e21c)
 * 📜 [Master the JavaScript Interview: What is a Pure Function? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-pure-function-d1c076bec976)
 * 📜 [JavaScript: What Are Pure Functions And Why Use Them? — James Jeffery](https://medium.com/@jamesjefferyuk/javascript-what-are-pure-functions-4d4d5392d49c)
 * 📜 [Pure functions in JavaScript — @nicoespeon](http://www.nicoespeon.com/en/2015/01/pure-functions-javascript/)
 * 📜 [Functional Programming: Pure Functions — Arne Brasseur](https://www.sitepoint.com/functional-programming-pure-functions/)
 * 📜 [Pure Functions In Javascript — Krunal](https://appdividend.com/2017/04/10/pure-functions-in-javascript/)
 * 📜 [Making your JavaScript Pure — Jack Franklin](https://alistapart.com/article/making-your-javascript-pure)
 * 📜 [To mutate, or not to mutate, in JavaScript](https://slemgrim.com/mutate-or-not-to-mutate/)
 * 📜 [Arrays, Objects and Mutations — Federico Knüssel](https://medium.com/@fknussel/arrays-objects-and-mutations-6b23348b54aa)
 * 📜 [The State of Immutability — Maciej Sikora](https://medium.com/dailyjs/the-state-of-immutability-169d2cd11310)
 * 📜 [How to deal with dirty side effects in your pure functional JavaScript — James Sinclair](https://jrsinclair.com/articles/2018/how-to-deal-with-dirty-side-effects-in-your-pure-functional-javascript/)
 * 📜 [Preventing Side Effects in JavaScript — David Walsh](https://davidwalsh.name/preventing-sideeffects-javascript)
 * 📜 [Wielding Pure Functions in JavaScript and Function Composition — Peleke Sengstacke
](https://scotch.io/tutorials/wielding-pure-functions-in-javascript-and-function-composition)
 * 📜 [JavaScript: Pure Functions — William S. Vincent](https://wsvincent.com/javascript-pure-functions/)
 * 📜 [Functional programming paradigms in modern JavaScript: Pure functions — Alexander Kondov](https://hackernoon.com/functional-programming-paradigms-in-modern-javascript-pure-functions-797d9abbee1)

 ### Videos

 * 🎥 [Pure Functions — Hexlet](https://www.youtube.com/watch?v=dZ41D6LDSBg)
 * 🎥 [Pure Functions - Functional Programming in JavaScript — Paul McBride](https://www.youtube.com/watch?v=Jh_Uzqzz_wM)
 * 🎥 [JavaScript Pure Functions — Seth Alexander](https://www.youtube.com/watch?v=frT3H-eBmPc)
 * 🎥 [JavaScript Pure vs Impure Functions Explained — Theodore Anderson](https://www.youtube.com/watch?v=AHbRVJzpB54)


**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 21. Closures

### Articles

 * 📜 [Closures — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Closures)
 * 📜 [I never understood JavaScript closures — Olivier De Meulder](https://medium.com/dailyjs/i-never-understood-javascript-closures-9663703368e8)
 * 📜 [Closure — JavaScript.Info](https://javascript.info/closure)
 * 📜 [Understand JavaScript Closures With Ease — Richard Bovell](http://javascriptissexy.com/understand-javascript-closures-with-ease/)
 * 📜 [Understanding JavaScript Closures — Codesmith](https://codeburst.io/understanding-javascript-closures-da6aab330302)
 * 📜 [Understand Closures in JavaScript — Brandon Morelli](https://codeburst.io/understand-closures-in-javascript-d07852fa51e7)
 * 📜 [A simple guide to help you understand closures in JavaScript — Prashant Ram](https://medium.freecodecamp.org/javascript-closures-simplified-d0d23fa06ba4)
 * 📜 [Understanding JavaScript Closures: A Practical Approach — Paul Upendo](https://scotch.io/tutorials/understanding-javascript-closures-a-practical-approach)
 * 📜 [Understanding JavaScript: Closures — Alexander Kondov](https://hackernoon.com/understanding-javascript-closures-4188edf5ea1b)
 * 📜 [How to use JavaScript closures with confidence — Léna Faure](https://hackernoon.com/how-to-use-javascript-closures-with-confidence-85cd1f841a6b)
 * 📜 [JavaScript closures by example — tyler](https://howchoo.com/g/mge2mji2mtq/javascript-closures-by-example)
 * 📜 [JavaScript — Closures and Scope — Alex Aitken](https://codeburst.io/javascript-closures-and-scope-3784c75b9290)
 * 📜 [Discover the power of closures in JavaScript — Cristi Salcescu](https://medium.freecodecamp.org/discover-the-power-of-closures-in-javascript-5c472a7765d7)
 * 📜 [Simplified JavaScript: Getting Started with Closures — Code Like A Girl](https://code.likeagirl.io/simplified-javascript-getting-started-with-closures-f40f65317d00)
 * 📜 [The Ultimate Guide to Hoisting, Scopes, and Closures in JavaScript — Tyler McGinnis](https://tylermcginnis.com/ultimate-guide-to-execution-contexts-hoisting-scopes-and-closures-in-javascript/)

 ### Videos

 * 🎥 [Javascript Closure — techsith](https://www.youtube.com/watch?v=71AtaJpJHw0)
 * 🎥 [Closures — Fun Fun Function](https://www.youtube.com/watch?v=CQqwU2Ixu-U)
 * 🎥 [Closures in JavaScript — techsith](https://www.youtube.com/watch?v=-xqJo5VRP4A)
 * 🎥 [JavaScript Closures 101: What is a closure? — JavaScript Tutorials](https://www.youtube.com/watch?v=yiEeiMN2Khs)
 * 🎥 [Closures — freeCodeCamp](https://www.youtube.com/watch?v=1JsJx1x35c0)
 * 🎥 [JavaScript Closures — CodeWorkr](https://www.youtube.com/watch?v=-rLrGAXK8WE)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 22. High Order Functions

### Articles

 * 📜 [Higher-Order Functions — Eloquent JavaScript [Book]](https://eloquentjavascript.net/05_higher_order.html)
 * 📜 [Higher-Order Functions in JavaScript — M. David Green](https://www.sitepoint.com/higher-order-functions-javascript/)
 * 📜 [Higher Order Functions: Using Filter, Map and Reduce for More Maintainable Code — Guido Schmitz](https://medium.freecodecamp.org/higher-order-functions-in-javascript-d9101f9cf528)
 * 📜 [First-class and Higher Order Functions: Effective Functional JavaScript — Hugo Di Francesco](https://hackernoon.com/effective-functional-javascript-first-class-and-higher-order-functions-713fde8df50a)
 * 📜 [Higher Order Functions in JavaScript — John Hannah](https://www.lullabot.com/articles/higher-order-functions-in-javascript)
 * 📜 [Higher-order Functions — Richard Bovell](http://javascriptissexy.com/tag/higher-order-functions/)
 * 📜 [Higher Order Functions in JavaScript — Zsolt Nagy](http://www.zsoltnagy.eu/higher-order-functions-in-javascript/)
 * 📜 [Fun With Higher Order Functions In JavaScript — Derick](https://derickbailey.com/2015/10/21/fun-with-higher-order-functions-in-javascript/)
 * 📜 [Just a reminder on how to use high order functions — Pedro Filho](https://github.com/pedroapfilho/high-order-functions)
 * 📜 [Understanding Higher-Order Functions in JavaScript — Sukhjinder Arora](https://blog.bitsrc.io/understanding-higher-order-functions-in-javascript-75461803bad)

 ### Videos

 * 🎥 [JavaScript Higher Order Functions & Arrays — Traversy Media](https://www.youtube.com/watch?v=rRgD1yVwIvE)
 * 🎥 [Higher Order Functions — Fun Fun Function](https://www.youtube.com/watch?v=BMUiFMZr7vk)
 * 🎥 [Higher Order Functions in Javascript — Raja Yogan](https://www.youtube.com/watch?v=dTlpYnmBW9I)
 * 🎥 [Higher Order Iterators in JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=GYRMNp1SKXA)
 * 🎥 [Higher Order Functions in JavaScript — The Coding Train](https://www.youtube.com/watch?v=H4awPsyugS0)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 23. Recursion

### Articles

 * 📜 [Recursion in JavaScript — Kevin Ennis](https://medium.freecodecamp.org/recursion-in-javascript-1608032c7a1f)
 * 📜 [Understanding Recursion in JavaScript — Zak Frisch](https://medium.com/@zfrisch/understanding-recursion-in-javascript-992e96449e03)
 * 📜 [Learn and Understand Recursion in JavaScript — Brandon Morelli](https://codeburst.io/learn-and-understand-recursion-in-javascript-b588218e87ea)
 * 📜 [Recursion in Functional JavaScript — M. David Green](https://www.sitepoint.com/recursion-functional-javascript/)
 * 📜 [Programming with JS: Recursion — Alexander Kondov](https://hackernoon.com/programming-with-js-recursion-31371e2bf808)
 * 📜 [Anonymous Recursion in JavaScript — simo](https://dev.to/simov/anonymous-recursion-in-javascript)
 * 📜 [Recursion, iteration and tail calls in JS — loverajoel](http://www.jstips.co/en/javascript/recursion-iteration-and-tail-calls-in-js/)
 * 📜 [Understanding Recursion in JavaScript with Confidence — Jay](https://www.thecodingdelight.com/understanding-recursion-javascript/)

 ### Videos

 * 🎥 [Recursion In JavaScript — techsith](https://www.youtube.com/watch?v=VtG0WAUvq2w)
 * 🎥 [Recursion — Fun Fun Function](https://www.youtube.com/watch?v=k7-N8R0-KY4)
 * 🎥 [Recursion and Recursive Functions — Hexlet](https://www.youtube.com/watch?v=vLhHyGTkjCs)
 * 🎥 [Recursion: Recursion() — JS Monthly — Lucas da Costa](https://www.youtube.com/watch?v=kGXVsd8pBLw)
 * 🎥 [Recursive Function in JavaScript — kudvenkat](https://www.youtube.com/watch?v=uyjsR9eNTIw)
 * 🎥 [What on Earth is Recursion? — Computerphile](https://www.youtube.com/watch?v=Mv9NEXX1VHc)
 * 🎥 [Javascript Tutorial 34: Introduction To Recursion — codedamn](https://www.youtube.com/watch?v=9NO5dXSlbv8)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 24. Collections and Generators

### Articles

 * 📜 [ES6 In Depth: Collections — Jason Orendorff](https://hacks.mozilla.org/2015/06/es6-in-depth-collections/)
 * 📜 [ES6 Collections: Using Map, Set, WeakMap, WeakSet — Kyle Pennell](https://www.sitepoint.com/es6-collections-map-set-weakmap-weakset/)
 * 📜 [ES6 WeakMaps, Sets, and WeakSets in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-weakmaps-sets-and-weaksets-in-depth)
 * 📜 [Introduction to Sets in JavaScript — Alligator.io](https://alligator.io/js/sets-introduction/)
 * 📜 [Introduction to Maps in JavaScript — Alligator.io](https://alligator.io/js/maps-introduction/)
 * 📜 [Map, Set, WeakMap and WeakSet — JavaScript.Info](https://javascript.info/map-set-weakmap-weakset)
 * 📜 [Maps in ES6 - A Quick Guide — Ben Mildren](https://dev.to/mildrenben/maps-in-es6---a-quick-guide-35pk)
 * 📜 [ES6 — Set vs Array — What and when? — Maya Shavin](https://medium.com/front-end-hacking/es6-set-vs-array-what-and-when-efc055655e1a)
 * 📜 [ES6 — Map vs Object — What and when? — Maya Shavin](https://medium.com/front-end-hacking/es6-map-vs-object-what-and-when-b80621932373)
 * 📜 [ES6: Working with Sets in JavaScript — Dead Code Rising](http://www.deadcoderising.com/es6-working-with-sets-in-javascript/)
 * 📜 [Array vs Set vs Map vs Object — Real-time use cases in Javascript (ES6/ES7) — Rajesh Babu](https://codeburst.io/array-vs-set-vs-map-vs-object-real-time-use-cases-in-javascript-es6-47ee3295329b)
 * 📜 [How to create an array of unique values in JavaScript using Sets — Claire Parker-Jones](https://dev.to/claireparker/how-to-create-an-array-of-unique-values-in-javascript-using-sets-5dg6)
 * 📜 [What You Should Know About ES6 Maps — Just Chris](https://hackernoon.com/what-you-should-know-about-es6-maps-dc66af6b9a1e)
 * 📜 [ES6 Maps in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-maps-in-depth)
 * 📜 [Generator — MDN web docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Generator)
* 📜 [What are JavaScript Generators and how to use them — Vladislav Stepanov](https://codeburst.io/what-are-javascript-generators-and-how-to-use-them-c6f2713fd12e)
* 📜 [Understanding JavaScript Generators With Examples  — Arfat Salman](https://codeburst.io/understanding-generators-in-es6-javascript-with-examples-6728834016d5)
* 📜 [The Basics of ES6 Generators — Kyle Simpson](https://davidwalsh.name/es6-generators)



 ### Videos

 * 🎥 [JavaScript ES6 / ES2015 Set, Map, WeakSet and WeakMap — Traversy Media](https://www.youtube.com/watch?v=ycohYSx5h9w)
 * 🎥 [The Differences between ES6 Maps and Sets — Steve Griffith](https://www.youtube.com/watch?v=m4abICrldQI)
 * 🎥 [Javascript Generators - THEY CHANGE EVERYTHING - ES6 Generators Harmony Generators — LearnCode.academy](https://www.youtube.com/watch?v=QO07THdLWQo)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 25. Promises

### Articles

 * 📜 [Promise — MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
 * 📜 [JavaScript Promises for Dummies ― Jecelyn Yeen](https://scotch.io/tutorials/javascript-promises-for-dummies)
 * 📜 [Understanding promises in JavaScript — Gokul N K](https://hackernoon.com/understanding-promises-in-javascript-13d99df067c1)
 * 📜 [Master the JavaScript Interview: What is a Promise? — Eric Elliott](https://medium.com/javascript-scene/master-the-javascript-interview-what-is-a-promise-27fc71e77261)
 * 📜 [An Overview of JavaScript Promises — Sandeep Panda](https://www.sitepoint.com/overview-javascript-promises/)
 * 📜 [How to use Promises in JavaScript — Prashant Ram](https://medium.freecodecamp.org/promises-in-javascript-explained-277b98850de)
 * 📜 [Implementing Promises In JavaScript — Maciej Cieslar](https://medium.freecodecamp.org/how-to-implement-promises-in-javascript-1ce2680a7f51)
 * 📜 [JavaScript: Promises explained with simple real life analogies — Shruti Kapoor](https://codeburst.io/javascript-promises-explained-with-simple-real-life-analogies-dd6908092138)
 * 📜 [Promises for Asynchronous Programming — Exploring JS](http://exploringjs.com/es6/ch_promises.html)
 * 📜 [JavaScript Promises Explained By Gambling At A Casino — Kevin Kononenko](https://blog.codeanalogies.com/2018/08/26/javascript-promises-explained-by-gambling-at-a-casino/)
 * 📜 [ES6 Promises: Patterns and Anti-Patterns — Bobby Brennan](https://medium.com/datafire-io/es6-promises-patterns-and-anti-patterns-bbb21a5d0918)
 * 📜 [A Simple Guide to ES6 Promises — Brandon Morelli](https://codeburst.io/a-simple-guide-to-es6-promises-d71bacd2e13a)
 * 📜 [The ES6 Promises — Manoj Singh Negi](https://codeburst.io/the-es6-promises-87a979ab27e4)
 * 📜 [ES6 Promises in Depth — Nicolás Bevacqua](https://ponyfoo.com/articles/es6-promises-in-depth)
 * 📜 [Playing with Javascript Promises: A Comprehensive Approach — Rajesh Babu](https://codeburst.io/playing-with-javascript-promises-a-comprehensive-approach-25ab752c78c3)

 ### Videos

 * 🎥 [Let's Learn ES6 - Promises — Ryan Christiani](https://www.youtube.com/watch?v=vQ3MoXnKfuQ)
 * 🎥 [JavaScript ES6 / ES2015 Promises — Traversy Media](https://www.youtube.com/watch?v=XJEHuBZQ5dU)
 * 🎥 [Promises — Fun Fun Function](https://www.youtube.com/watch?v=2d7s3spWAzo)
 * 🎥 [Error Handling Promises in JavaScript — Fun Fun Function](https://www.youtube.com/watch?v=f8IgdnYIwOU)
 * 🎥 [Promises Part 1 - Topics of JavaScript/ES6 — The Coding Train](https://www.youtube.com/watch?v=QO4NXhWo_NM)
 
**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 26. async/await

### Articles

 * 📜 [async/await — JavaScript.Info](https://javascript.info/async-await)
 * 📜 [Understanding async/await in Javascript — Gokul N K](https://hackernoon.com/understanding-async-await-in-javascript-1d81bb079b2c)
 * 📜 [Asynchronous Programming — Eloquent JavaScript](https://eloquentjavascript.net/11_async.html)
 * 📜 [Exploring Async/Await Functions in JavaScript — Alligator.io](https://alligator.io/js/async-functions/)
 * 📜 [Asynchronous Javascript using async/await — Joy Warugu](https://scotch.io/tutorials/asynchronous-javascript-using-async-await)
 * 📜 [Modern Asynchronous JavaScript with async/await — Flavio Copes](https://flaviocopes.com/javascript-async-await/)
 * 📜 [Asynchronous JavaScript: From Callback Hell to Async and Await — Demir Selmanovic](https://www.toptal.com/javascript/asynchronous-javascript-async-await-tutorial)
 * 📜 [Javascript — ES8 Introducing async/await Functions — Ben Garrison](https://medium.com/@_bengarrison/javascript-es8-introducing-async-await-functions-7a471ec7de8a)
 * 📜 [How to escape async/await hell — Aditya Agarwal](https://medium.freecodecamp.org/avoiding-the-async-await-hell-c77a0fb71c4c)
 * 📜 [Understanding JavaScript’s async await — Nicolás Bevacqua](https://ponyfoo.com/articles/understanding-javascript-async-await)
 * 📜 [JavaScript Async/Await: Serial, Parallel and Complex Flow — TechBrij](https://techbrij.com/javascript-async-await-parallel-sequence)
 * 📜 [Asynchronous Programming — Exploring JS](http://exploringjs.com/es6/ch_async.html)
 * 📜 [From JavaScript Promises to Async/Await: why bother? — Chris Nwamba](https://blog.pusher.com/promises-async-await/)
 * 📜 [Flow Control in Modern JS: Callbacks to Promises to Async/Await — Craig Buckler](https://www.sitepoint.com/flow-control-callbacks-promises-async-await/)
 * 📜 [JavaScript: Promises and Why Async/Await Wins the Battle — Nick Parsons](https://dzone.com/articles/javascript-promises-and-why-asyncawait-wins-the-ba)

 ### Videos

 * 🎥 [Async + Await — Wes Bos](https://www.youtube.com/watch?v=9YkUCxvaLEk)
 * 🎥 [Asynchrony: Under the Hood — Shelley Vohr](https://www.youtube.com/watch?v=SrNQS8J67zc)
 * 🎥 [async/await in JavaScript - What, Why and How — Fun Fun Function](https://www.youtube.com/watch?v=568g8hxJJp4&index=3&list=PL0zVEGEvSaeHJppaRLrqjeTPnCH6)
 * 🎥 [async/await Part 1 - Topics of JavaScript/ES8 — The Coding Train](https://www.youtube.com/watch?v=XO77Fib9tSI&index=3&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)
 * 🎥 [async/await Part 2 - Topics of JavaScript/ES8 — The Coding Train](https://www.youtube.com/watch?v=chavThlNz3s&index=4&list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 27. Data Structures

### Articles

 * 📜 [Data Structures in JavaScript — Thon Ly](https://medium.com/siliconwat/data-structures-in-javascript-1b9aed0ea17c)
 * 📜 [Algorithms and Data Structures in JavaScript — Oleksii Trekhleb](https://itnext.io/algorithms-and-data-structures-in-javascript-a71548f902cb)
 * 📜 [Data Structures: Objects and Arrays ― Chris Nwamba](https://scotch.io/courses/10-need-to-know-javascript-concepts/data-structures-objects-and-arrays)
 * 📜 [Data structures in JavaScript — Benoit Vallon](http://blog.benoitvallon.com/data-structures-in-javascript/data-structures-in-javascript/)
 * 📜 [Playing with Data Structures in Javascript — Anish K.](https://blog.cloudboost.io/playing-with-data-structures-in-javascript-stack-a55ebe50f29d)
 * 📜 [The Little Guide of Queue in JavaScript — Germán Cutraro](https://hackernoon.com/the-little-guide-of-queue-in-javascript-4f67e79260d9)
 * 📜 [All algorithms writing with JavaScript in the book 'Algorithms Fourth Edition'](https://github.com/barretlee/algorithms)
 * 📜 [Collection of classic computer science paradigms in JavaScript](https://github.com/nzakas/computer-science-in-javascript)
 * 📜 [All the things you didn't know you wanted to know about data structures](https://github.com/jamiebuilds/itsy-bitsy-data-structures)

 ### Videos

 * 🎥 [Algorithms in JavaScript — Seth Koch](https://www.youtube.com/watch?v=PylQlISSH8U&list=PLujX4CIdBGCa-65N3uN8CDbUMrYsHBrz-)
 * 🎥 [Algorithms In Javascript | Ace Your Interview — Eduonix Learning Solutions](https://www.youtube.com/watch?v=H_EBPZgiAas&list=PLDmvslp_VR0zYUSth_8O69p4_cmvZEgLa)
 * 🎥 [Data Structures and Algorithms in JavaScript — freeCodeCamp](https://www.youtube.com/watch?v=Gj5qBheGOEo&list=PLWKjhJtqVAbkso-IbgiiP48n-O-JQA9PJ)
 * 🎥 [Learning JavaScript Data Structures and Algorithms: Sorting — Packt Video](https://www.youtube.com/watch?v=Ymh_AurrMbA)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 28. Expensive Operation and Big O Notation

### Articles

 * 📜 [Big O Notation in Javascript — César Antón Dorantes](https://medium.com/cesars-tech-insights/big-o-notation-javascript-25c79f50b19b)
 * 📜 [Time Complexity/Big O Notation — Tim Roberts](https://medium.com/javascript-scene/time-complexity-big-o-notation-1a4310c3ee4b)
 * 📜 [Big O in JavaScript — Gabriela Medina](https://medium.com/@gmedina229/big-o-in-javascript-36ff67766051)
 * 📜 [Big O Search Algorithms in JavaScript — Bradley Braithwaite](http://www.bradoncode.com/blog/2012/04/big-o-algorithm-examples-in-javascript.html)
 * 📜 [Time Complexity Analysis in JavaScript — Jennifer Bland](https://www.jenniferbland.com/time-complexity-analysis-in-javascript/)
 * 📜 [Algorithms in plain English: time complexity and Big-O Notation — Michael Olorunnisola](https://medium.freecodecamp.org/time-is-complex-but-priceless-f0abd015063c)

### Videos

 * 🎥 [JavaScript: Intro to Big O Notation and Function Runtime — Eric Traub](https://www.youtube.com/watch?v=HgA5VOFan5E)
 * 🎥 [Essential Big O for JavaScript Developers — Dave Smith](https://www.youtube.com/watch?v=KatlvCFHPRo)
 * 🎥 [Big O Notation - Time Complexity Analysis — WebTunings](https://www.youtube.com/watch?v=ALl86xJiTD8)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 29. Algorithms

### Articles

 * 📜 [Data Structures and Algorithms using ES6](https://github.com/Crizstian/data-structure-and-algorithms-with-ES6)
 * 📜 [Algorithms and data structures implemented in JavaScript with explanations and links to further readings](https://github.com/trekhleb/javascript-algorithms)
 * 📜 [JS: Interview Algorithm](http://www.thatjsdude.com/interview/js1.html)
 * 📜 [Algorithms in JavaScript — Thon Ly](https://medium.com/siliconwat/algorithms-in-javascript-b0bed68f4038)
 * 📜 [JavaScript Objects, Square Brackets and Algorithms — Dmitri Grabov](https://medium.freecodecamp.org/javascript-objects-square-brackets-and-algorithms-e9a2916dc158)
 * 📜 [Atwood's Law applied to CS101 - Classic algorithms and data structures implemented in JavaScript](https://github.com/felipernb/algorithms.js)
 * 📜 [Data Structures and Algorithms library in JavaScript](https://github.com/yangshun/lago)
 * 📜 [Collection of computer science algorithms and data structures written in JavaScript](https://github.com/idosela/algorithms-in-javascript)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 30. Inheritance, Polymorphism and Code Reuse

### Articles

 * 📜 [Class inheritance, super — JavaScript.Info](https://javascript.info/class-inheritance)
 * 📜 [Inheritance in JavaScript — MDN](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Inheritance)
 * 📜 [Inheritance in JavaScript — Rupesh Mishra](https://hackernoon.com/inheritance-in-javascript-21d2b82ffa6f)
 * 📜 [Simple Inheritance with JavaScript — David Catuhe](https://www.sitepoint.com/simple-inheritance-javascript/)
 * 📜 [JavaScript — Inheritance, delegation patterns and Object linking — NC Patro](https://codeburst.io/javascript-inheritance-25fe61ab9f85)
 * 📜 [Object Oriented JavaScript: Polymorphism with examples — Knoldus Blogs](https://blog.knoldus.com/object-oriented-javascript-polymorphism-with-examples/)
 * 📜 [Program Like Proteus — A beginner’s guide to polymorphism in Javascript — Sam Galson](https://medium.com/yld-engineering-blog/program-like-proteus-a-beginners-guide-to-polymorphism-in-javascript-867bea7c8be2)
 * 📜 [Object-oriented JavaScript: A Deep Dive into ES6 Classes — Jeff Mott](https://www.sitepoint.com/object-oriented-javascript-deep-dive-es6-classes/)

  ### Videos

 * 🎥 [Inheritance in JavaScript — kudvenkat](https://www.youtube.com/watch?v=yXlFR81tDBM)
 * 🎥 [JavaScript ES6 Classes and Inheritance — Traversy Media](https://www.youtube.com/watch?v=RBLIm5LMrmc)
 * 🎥 [Polymorphism in JavaScript — kudvenkat](https://www.youtube.com/watch?v=zdovG9cuEBA)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 31. डिजाइन पैटर्न्स

### सामग्री

 * 📜 [4 जावास्क्रिप्ट डिजाइन पैटर्न आपको पता होना चाहिए - देवन पटेल](https://scotch.io/bar-talk/4-javascript-design-patterns-you-should-know)
 * 📜 [जावास्क्रिप्ट डिज़ाइन पैटर्न - शुरुआती गाइड मोबाइल वेब डेवलपमेंट - सौमजीत पाठक](https://medium.com/beginners-guide-to-mobile-web-development/javascript-design-patterns-25f0faaaa15)
 * 📜 [जावास्क्रिप्ट डिजाइन पैटर्न - आकाश पाल](https://medium.com/front-end-hacking/javascript-design-patterns-ed9d4c144c81)
 * 📜 [जावास्क्रिप्ट डिजाइन पैटर्न: वे क्या हैं और उनका उपयोग कैसे करें - पैट्रिक सिम्पसन](https://seesparkbox.com/foundry/javascript_design_patterns)
 * 📜 [जावास्क्रिप्ट डिजाइन पैटर्न: जावास्क्रिप्ट में डिजाइन पैटर्न को समझना - सुखजींदर अरोड़ा](https://blog.bitsrc.io/understanding-design-patterns-in-javascript-13345223f2dd)
 * 📜 [जावास्क्रिप्ट - फेलिप बेलिन में लागू सभी 23 (GoF) डिजाइन पैटर्न](https://github.com/fbeline/Design-Patterns-JS)
 * 📜 [जावास्क्रिप्ट डिजाइन पैटर्न सीखना - Addy Osmani ](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)


  ### वीडियो

 * 🎥 [जावास्क्रिप्ट डिजाइन पैटर्न - Udacity](https://www.udacity.com/course/javascript-design-patterns--ud989)
 * 🎥 [2017 के लिए जावास्क्रिप्ट पैटर्न - स्कॉट एलन](https://www.youtube.com/watch?v=hO7mzO83N1Q)

 **[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 32. आंशिक अनुप्रयोग, करी, रचना और पाइप

### सामग्री

 * 📜 [जावास्क्रिप्ट में फ़ंक्शन संरचना का उपयोग करें - रेमी](https://www.codementor.io/michelre/use-function-composition-in-javascript-gkmxos5mj)
 * 📜 [जावास्क्रिप्ट ES6 में आ रहा है - एडम बेने](https://blog.benestudio.co/currying-in-javascript-es6-540d2ad09400)
 * 📜 [जावास्क्रिप्ट में रचना और करीबी लालित्य - प्रगति दास](https://medium.com/@pragyan88/writing-middleware-composition-and-currying-elegance-in-javascript-8b15c98a541b)
 * 📜 [कार्यात्मक जावास्क्रिप्ट: हर दिन उपयोग के लिए फंक्शन संरचना - जोएल थॉमस](https://hackernoon.com/javascript-functional-composition-for-every-day-use-22421ef65a10)
 * 📜 [कार्यात्मक संरचना: लिखें () और पाइप () - एंटोन पारस](https://medium.com/@acparas/what-i-learned-today-july-2-2017-ab9a46dbf85f)
 * 📜 [क्यों हिपस्टर्स सब कुछ लिखें: जावास्क्रिप्ट में कार्यात्मक रचना - ए शरीफ़](http://busypeoples.github.io/post/functional-composing-javascript/)
 * 📜 [कार्यात्मक जावास्क्रिप्ट पीटी III के लिए एक जमे हुए परिचय III: कार्यों को बनाने के लिए कार्य - जेम्स सिंक्लेयर](https://jrsinclair.com/articles/2016/gentle-introduction-to-functional-javascript-functions/)
 * 📜 [करी और लिखें (आपको अपने कोड में रामडा की तरह कुछ क्यों उपयोग करना चाहिए) - jsanchesleao](https://jsleao.wordpress.com/2015/02/22/curry-and-compose-why-you-should-be-using-something-like-ramda-in-your-code/)
 * 📜 [पाइप के साथ जावास्क्रिप्ट में फंक्शन संरचना - एंडी वैन स्लैर्स](https://vanslaars.io/post/create-pipe-function/)
 * 📜 [रामदा के साथ व्यावहारिक कार्यात्मक जावास्क्रिप्ट - एंड्रयू डी'एमेलियो, यूरी तख्तटेव](https://developer.telerik.com/featured/practical-functional-javascript-ramda/)
 * 📜 [आंशिक अनुप्रयोग, करी, और समारोह संरचना में सौंदर्य - जोएल थॉमस](https://hackernoon.com/the-beauty-in-partial-application-currying-and-function-composition-d885bdf0d574)
 * 📜 [करी या आंशिक आवेदन? - एरिक इलियट](https://medium.com/javascript-scene/curry-or-partial-application-8150044c78b8)
 * 📜 [जावास्क्रिप्ट में आंशिक आवेदन - बेन आलमैन](http://benalman.com/news/2012/09/partial-application-in-javascript/)
 * 📜 [कार्यों का आंशिक अनुप्रयोग - कार्यात्मक प्रतिक्रियाशील निंजा](https://hackernoon.com/partial-application-of-functions-dbe7d9b80760)
 * 📜 [करीबी बनाम आंशिक आवेदन - दीपक गुप्ता](https://codeburst.io/javascript-currying-vs-partial-application-4db5b2442be8)
 * 📜 [ईसीएमएस्क्रिप्ट 2015 में आंशिक आवेदन - रागन वाल्ड](http://raganwald.com/2015/04/01/partial-application.html)
 * 📜 [जावास्क्रिप्ट में कार्यात्मक संरचना - जो कोर्तोपासी](https://joecortopassi.com/articles/functional-composition-in-javascript/)
 * 📜 [तो आप एक कार्यात्मक प्रोग्रामर बनना चाहते हैं pt.। मैं - चार्ल्स स्काफानी](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-1-1f15e387e536)
 * 📜 [तो आप एक कार्यात्मक प्रोग्रामर बनना चाहते हैं -pt. II - चार्ल्स स्काफानी](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-2-7005682cec4a)
 * 📜 [तो आप एक कार्यात्मक प्रोग्रामर बनना चाहते हैं- pt. III - चार्ल्स स्काफानी](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-3-1b0fd14eb1a7)
 * 📜 [तो आप एक कार्यात्मक प्रोग्रामर बनना चाहते हैं -pt. IV - चार्ल्स स्काफानी](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-4-18fbe3ea9e49)
 * 📜 [तो आप एक कार्यात्मक प्रोग्रामर बनना चाहते हैं -pt. V - चार्ल्स स्काफानी](https://medium.com/@cscalfani/so-you-want-to-be-a-functional-programmer-part-5-c70adc9cf56a)
 * 📜 [कार्यात्मक-प्रकाश जावास्क्रिप्ट अध्याय 3: प्रबंधन फ़ंक्शन इनपुट - केली सिम्पसन](https://github.com/getify/Functional-Light-JS/blob/master/manuscript/ch3.md)
 * 📜 [कार्यात्मक प्रोग्रामिंग के बुनियादी सिद्धांतों के लिए एक परिचय - टीके](https://medium.freecodecamp.org/an-introduction-to-the-basic-principles-of-functional-programming-a2c2a15c84)
 * 📜 [जावास्क्रिप्ट में कार्यात्मक प्रोग्रामिंग की अवधारणाओं - टीके](https://medium.com/the-renaissance-developer/concepts-of-functional-programming-in-javascript-6bc84220d2aa)

  ### वीडियो

 * 🎥 [लिखें बनाम पाइप: जावास्क्रिप्ट में कार्यात्मक प्रोग्रामिंग — शैल्ड स्टूडियो](https://www.youtube.com/watch?v=Wl2ejJOqHUU)
 * 🎥 [जावास्क्रिप्ट कार्यात्मक प्रोग्रामिंग: कम्पोज़ - थियोडोर एंडरसन](https://www.youtube.com/watch?v=jigHxo9YR30)
 * 🎥 [फंक्शन संरचना - कार्यात्मक जावास्क्रिप्ट - NWCalvank](https://www.youtube.com/watch?v=mth5WpEc4Qs)
 * 🎥 [जावास्क्रिप्ट फंक्शन संरचना समझाया - थियोडोर एंडरसन](https://www.youtube.com/watch?v=Uam37AlzPYw)
 * 🎥 [फ़ंक्शन फ़ंक्शन के साथ कोड करें - मज़ा मज़ा फ़ंक्शन](https://www.youtube.com/watch?v=VGB9HbL1GHk)
 * 🎥 [आंशिक अनुप्रयोग बनाम करी - एनडब्ल्यू कैलवान](https://www.youtube.com/watch?v=DzLkRsUN2vE)
 * 🎥 [जावास्क्रिप्ट आंशिक अनुप्रयोग - थियोडोर एंडरसन](https://www.youtube.com/watch?v=jkebgHEcvac)

**[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**

---

## 33. स्वच्छ कोड

### सामग्री

 * 📜 [जावास्क्रिप्ट के लिए अनुकूलित स्वच्छ कोड अवधारणाओं - रयान मैकडर्मॉट](https://github.com/ryanmcdermott/clean-code-javascript)
 * 📜 [जावास्क्रिप्ट स्वच्छ कोडिंग सर्वोत्तम अभ्यास - एंड्रस टोथ](https://blog.risingstack.com/javascript-clean-coding-best-practices-node-js-at-scale/)
 * 📜 [जावास्क्रिप्ट स्वच्छ कोड - केविन पीटर्स में फंक्शन पैरामीटर](https://medium.com/@kevin_peters/function-parameters-in-javascript-clean-code-4caac109159b)
 * 📜 [स्वच्छ कोड जावास्क्रिप्ट - सारा ड्रैसरर](https://css-tricks.com/clean-code-javascript/)
 * 📜 [अपने कोड को साफ रखना - सैमुअल जेम्स](https://codeburst.io/keeping-your-code-clean-d30bcffd1a10)
 * 📜 [आधुनिक जावास्क्रिप्ट सिंटेक्स का उपयोग करने के लिए सर्वोत्तम अभ्यास - एम डेविड ग्रीन](https://www.sitepoint.com/modern-javascript-best-practices/)

### वीडियो
*  🎥 [जावास्क्रिप्ट प्रो टिप्स - कोड यह, नहीं](https://www.youtube.com/watch?v=Mus_vwhTCq0)

 **[⬆ शीर्ष पर वापस जाएँ](#table-of-contents)**
