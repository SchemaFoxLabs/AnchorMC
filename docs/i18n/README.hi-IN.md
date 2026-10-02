<p align="center"><img src="../../icon.png" alt="AnchorMC icon" width="128"></p>

# AnchorMC

Minecraft 1.8 पर आधारित आधुनिक PvP सर्वर, जिसमें PracticePvP, आयोजन, PartyPvP और अन्य गेमप्ले हैं।

*Schema’Fox Labs द्वारा पुनर्निर्मित*

---

[English](../../README.md) · [中文](README.zh.md) · [日本語](README.ja-JP.md) · **हिन्दी**

AnchorMC, बंद हो चुके NetherMC का पूर्ण पुनर्निर्माण है और लाभ कमाने के उद्देश्य के बिना संचालित सामुदायिक परियोजना है।

> भाषा संस्करणों में अंतर या अस्पष्टता होने पर सर्वर और समुदाय के नियमों के लिए अंग्रेज़ी संस्करण मान्य होगा।

> अंग्रेज़ी सहित किसी भी संस्करण में नियमों की भाषा, अनुवाद के अंतर या अस्पष्टता को [Security and quality](https://github.com/SchemaFoxLabs/AnchorMC/security) में **Report a vulnerability** चुनकर स्पष्टता और सुधार के लिए बताया जा सकता है।

सुरक्षा समस्या की रिपोर्ट करने के लिए Security पृष्ठ पर **Report a vulnerability** चुनें। यदि यह विकल्प उपलब्ध नहीं है, तो केवल निजी संपर्क का तरीका पूछने के लिए Issue खोलें; सुरक्षा खामी का विवरण सार्वजनिक न करें।

_यह रिपॉज़िटरी सर्वर के सार्वजनिक feedback और update record का माध्यम है।_
_इसमें clone करने योग्य source code या deploy करने योग्य server build नहीं है और परियोजना की नीति के अनुसार Pull Request स्वीकार नहीं किए जाते।_
_Feedback या bug report के लिए Issues का उपयोग करें।_

## सामान्य दस्तावेज़ और सुविधाएँ

- [सर्वर और समुदाय के नियम](SERVER_RULES.hi-IN.md)
- [खिलाड़ी रिपोर्ट／अपील](https://github.com/Labs-mcdev/AnchorMC-PublicReport/)
- [सुरक्षा समस्या रिपोर्ट करें](https://github.com/SchemaFoxLabs/AnchorMC/security)
- [Feature request／Feedback](https://github.com/SchemaFoxLabs/AnchorMC/issues/new/choose)
- [Development log](https://github.com/SchemaFoxLabs/AnchorMC/releases)
- [Event record／archive](../../Events/)
- [Client optimization Mod](https://github.com/Labs-mcdev/VanillaEnhance)
- [गेमप्ले सुविधाएँ और मैकेनिक्स](GAMEPLAY_FEATURES.hi-IN.md)
- आधिकारिक साइट (soon)

---

## विषय सूची

- [परियोजना का परिचय](#परियोजना-का-परिचय)
- [प्रतिक्रिया और समस्याओं की निगरानी](#प्रतिक्रिया-और-समस्याओं-की-निगरानी)
- [सर्वर और बुनियादी कमांड](#सर्वर-और-बुनियादी-कमांड)
- [सहयोगियों के लिए पुरस्कार](#सहयोगियों-के-लिए-पुरस्कार)
- [नियम और संचालन](#नियम-और-संचालन)
- [परियोजना का इतिहास](#परियोजना-का-इतिहास)
- [विशेष आभार](#विशेष-आभार)

## परियोजना का परिचय

AnchorMC एक प्रतिस्पर्धी Minecraft server project है, जिसका लक्ष्य एशियाई खिलाड़ियों को आधुनिक PvP अनुभव देना है।

Schema’Fox Labs ने AnchorMC को फिर से बनाया और इसका रखरखाव करता है। इसमें classic 1.8 PvP mechanics को नई technology, optimized infrastructure और creative gameplay designs के साथ जोड़ा गया है।

हमारा लक्ष्य नए अनुभव प्रस्तुत करते हुए पुराने Minecraft को बनाए रखना है।

## प्रतिक्रिया और समस्याओं की निगरानी

Bug report, प्रश्न या feature request भेजने से पहले [feedback rules (English)](../FeedbackRule_QA-SI.md) पढ़ें।

> [!IMPORTANT]
> ठोस समस्या या आवश्यकता स्पष्ट रूप से बताएँ। केवल व्यक्तिपरक राय या ठोस जानकारी के बिना भेजी गई प्रतिक्रिया पर कार्रवाई संभव नहीं हो सकती है।

> [!WARNING]
> पुष्टि करें कि आपकी रिपोर्ट आपके देखे गए तथ्य को सही रूप से बताती है।
>
> सार्वजनिक Issues दूसरे लोग भी देख सकते हैं। वास्तविक नाम, निजी संपर्क, पहचान बताने वाली जानकारी और वास्तविक स्थान दिखाने वाली जानकारी को text, logs और screenshots से हटाएँ; प्रकाशित जानकारी पूरी तरह वापस नहीं ली जा सकती।

Staff उपलब्ध समय और प्रमाण के अनुसार submissions की समीक्षा करते हैं। कुछ feedback लंबे समय तक लंबित रह सकता है।

सामान्यतः 1–7 दिन और व्यस्त समय में 8–30 दिन शुरुआती कार्रवाई या पहले उत्तर के अनुमान हैं और इनसे अधिक समय लग सकता है, विशेषकर feature requests में। ये जाँच, समाधान या दंड की समय-सीमाएँ नहीं हैं।

Feature requests की आवश्यकता, व्यवहार्यता, development schedule और मौजूदा architecture के साथ compatibility की समीक्षा की जाती है।

Security से असंबंधित सामान्य functional bugs, गंभीर होने पर भी, Bug report form से भेजें। Vulnerabilities या exploit हो सकने वाली समस्याओं के लिए ऊपर दिए Security पृष्ठ का उपयोग करें।

Staff के offline होने पर खिलाड़ी reports या Join Block, Feature Block, SubServer Block की गलत कार्रवाई की अपील के लिए [AnchorMC-PublicReport](https://github.com/Labs-mcdev/AnchorMC-PublicReport/) का उपयोग करें।

## सर्वर और बुनियादी कमांड

सर्वर बदलने के लिए:

```minecraft-command
/server <identification>
```

| सर्वर | आंतरिक पहचान | विवरण | Minecraft संस्करण |
| :--- | :--- | :--- | :--- |
| Practice | `practice` | 1v1 मुकाबलों, आयोजनों और PartyPvP वाला आधुनिक Practice PvP | core 1.8.x; client 1.7.10–1.20.x |
| Bridge | `bridge` | bridge बनाना, लड़ाई और block placement का अभ्यास | core 1.8.x; client 1.7.10–1.20.x |
| Flat-PVP | `flatpvp/flat` | अत्यधिक knockback के साथ विरोधियों को हराना | core 1.8.x; client 1.7.10–1.20.x |
| Sky PVP | `skypvp` | संसाधन इकट्ठा करना और अलग-अलग प्रभाव वाले उपकरण खरीदना | core 1.8.x; client 1.7.10–1.20.x |
| PracticeX | soon | 1.20.x के लिए Practice PvP | core 1.20.x; client 1.7.10–1.20.x |
| 1.9+ | soon | तलवार से मुकाबला | core 1.12.2; client 1.7.10–1.20.x |

बजट की सीमाओं के कारण कम player activity वाले कुछ server अस्थायी रूप से offline हो सकते हैं। Practice सामान्यतः online रहता है।

## सहयोगियों के लिए पुरस्कार

गंभीर vulnerability, bug या security problem की रिपोर्ट सत्यापित होने और शर्तें पूरी होने पर:

- लंबे समय तक मान्य Support Rank।
- सार्वजनिक contributor recognition (सूची लंबी होने पर अलग दस्तावेज़ में जा सकती है)।

Rank रिपोर्ट के मूल्य और संख्या के आधार पर बढ़ता है:

**Support → SupportX → BugFinder → IssueExpert**

पुरस्कार की पात्रता Staff द्वारा सत्यापित की जाती है। केवल भेजने या स्वीकार होने से पुरस्कार नहीं मिलता। ये खरीद से असंबंधित योगदान पुरस्कार हैं और भविष्य के financial contribution से जुड़े नहीं हैं।

## नियम और संचालन

- [सर्वर और समुदाय के नियम](SERVER_RULES.hi-IN.md)
- [गेमप्ले सुविधाएँ और मैकेनिक्स](GAMEPLAY_FEATURES.hi-IN.md)
- [सर्वर का उपयोग और संचालन](SERVER_TERMS.hi-IN.md)
- [कॉपीराइट और तीसरे पक्ष की सामग्री](ASSET_RIGHTS.hi-IN.md)

सर्वर अभी cosmetics, permissions या अन्य paid content नहीं बेचता और sponsorships, donations या payments स्वीकार नहीं करता। भविष्य में authenticated Minecraft online accounts वाले खिलाड़ियों को actual server hosting costs में सीधे योगदान देने की सुविधा पर विचार किया जा सकता है; उपलब्ध होने से पहले अलग से बताया जाएगा।

## परियोजना का इतिहास

मूल server NightCelest और Tiantang ने बनाया था। Schema’Fox Labs ने इसे फिर से बनाया; Alice Tuna और nullindex ने technology, system design और rebuilding में योगदान दिया। AnchorMC classic PvP foundations को बनाए रखते हुए नए अनुभव विकसित कर रहा है।

---

## विशेष आभार

### मूल server के निर्माता

- [NightCelest](https://github.com/a3087814532)
- Tiantang (कोई सार्वजनिक social media profile नहीं मिली)

### System, gameplay, UI/UX design और experience architecture

- [Alice Tuna](https://github.com/LocalHost0080)

### Technology

- [nullindex](https://github.com/error-nullindex)

### Map resource providers

- [Alice Tuna](https://github.com/LocalHost0080)
- [rido](https://builtbybit.com/members/rido.331767/)
- [thegetawxy](https://www.planetminecraft.com/project/slime-arena-duel-pvp/)
- [Redstone Labs](https://builtbybit.com/members/redstone-labs.268653/)
- [betapaste](https://builtbybit.com/members/betapaste.512624/)
- [ColoN_](https://builtbybit.com/members/colon_.468523/)
- [PokyBuilds](https://builtbybit.com/members/pokybuilds.531551/)
- [zsomborr](https://builtbybit.com/members/zsomborr.335177/)
- [Solar Studios](https://builtbybit.com/members/solar-studios.500547/)

Map resources या system design contributions के registration या correction के लिए `mc-s-reg@schemafoxlabs.com` से संपर्क करें।

---

*यह प्राथमिकता केवल AnchorMC के अपने नियमों पर लागू है; यह तीसरे पक्ष के लाइसेंस, प्लेटफ़ॉर्म के नियम या लागू कानून के तहत न हटाए जा सकने वाले अधिकारों को नहीं बदलती।*

*यह परियोजना Mojang या Microsoft से संबद्ध नहीं है और उनसे अनुमोदित नहीं है।*

Regards,

@SchemaFoxLabs 2026
