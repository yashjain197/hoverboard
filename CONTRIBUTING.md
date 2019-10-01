## Guide for Contributors

Hoverboard are built in the open, and the GDG[x] team eagerly encourage any and all forms of community contribution. When contributing, please follow these guidelines:

### Filing Issues

**If you are filing an issue to request a feature**, please provide a clear description of the feature. It can be helpful to describe answers to the following questions:

 1. **Who will use the feature?** _“As someone filling out a form…”_
 2. **When will they use the feature?** _“When I enter an invalid value…”_
 3. **What is the user’s goal?** _“I want to be visually notified that the value needs to be corrected…”_

**If you are filing an issue to report a bug**, please provide:

 1. **A clear description of the bug and related expectations.** Consider using the following example template for reporting a bug:

 ```markdown
 
 The `paper-foo` element causes the page to turn pink when clicked.

 ## Expected outcome

 The page stays the same color.

 ## Actual outcome

 The page turns pink.

 ## Steps to reproduce

 1. Put a `paper-foo` element in the page.
 2. Open the page in a web browser.
 3. Click the `paper-foo` element.
 
 ```

 3. **A list of browsers where the problem occurs.** This can be skipped if the problem is the same across all browsers.

### Submitting Pull Requests

**Before creating a pull request**, please ensure that an issue exists for the corresponding change in the pull request that you intend to make. **If an issue does not exist, please create one per the guidelines above**. The goal is to discuss the design and necessity of the proposed change with Polymer authors and community before diving into a pull request.

When submitting pull requests, please provide:

 1. **A reference to the corresponding issue** or issues that will be closed by the pull request. Please refer to these issues in the pull request description using the following syntax:

 ```markdown
 (For a single issue)
 Fixes #20

 (For multiple issues)
 Fixes #32, fixes #40
 ```

 2. **A succinct description of the design** used to fix any related issues. For example:

 ```markdown
 This fixes #20 by removing styles that leaked which would cause the page to turn pink whenever `paper-foo` is clicked.
 ```

 3. **At least one test for each bug fixed or feature added** as part of the pull request. Pull requests that fix bugs or add features without accompanying tests will not be considered.

If a proposed change contains multiple commits, please [squash commits](https://www.google.com/url?q=http://blog.steveklabnik.com/posts/2012-11-08-how-to-squash-commits-in-a-github-pull-request) to as few as is necessary to succinctly express the change. A Polymer author can help you squash commits, so don’t be afraid to ask us if you need help with that!



_Copied from [Polymer Elements contributing guide](https://github.com/PolymerElements/ContributionGuide/blob/master/CONTRIBUTING.md)_
योगदानकर्ताओं के लिए गाइड
होवरबोर्ड खुले में बनाया गया है, और जीडीजी [एक्स] टीम सामुदायिक योगदान के किसी भी और सभी रूपों को उत्सुकता से प्रोत्साहित करती है। योगदान करते समय, कृपया इन दिशानिर्देशों का पालन करें:

फाइलिंग मुद्दे
यदि आप किसी सुविधा का अनुरोध करने के लिए कोई समस्या दर्ज कर रहे हैं, तो कृपया सुविधा का स्पष्ट विवरण प्रदान करें। निम्नलिखित सवालों के जवाब देने में मददगार हो सकता है:

सुविधा का उपयोग कौन करेगा? "जैसा कि कोई एक फॉर्म भर रहा है ..."
वे कब सुविधा का उपयोग करेंगे? "जब मैं एक अमान्य मान दर्ज करता हूं ..."
उपयोगकर्ता का लक्ष्य क्या है? "मैं दृष्टिगत रूप से अधिसूचित होना चाहता हूं कि मूल्य को ठीक करने की आवश्यकता है ..."
यदि आप बग की रिपोर्ट करने के लिए कोई समस्या दर्ज कर रहे हैं, तो कृपया प्रदान करें:

बग और संबंधित अपेक्षाओं का स्पष्ट विवरण। बग की रिपोर्ट करने के लिए निम्नलिखित उदाहरण टेम्पलेट का उपयोग करने पर विचार करें:
`पेपर-फ़ू` तत्व पेज को क्लिक करने पर गुलाबी होने का कारण बनता है।

## अनुमानित परिणाम

पेज उसी रंग का रहता है।

## वास्तविक परिणाम

पृष्ठ गुलाबी हो जाता है।

## प्रजनन करने कि प्रक्रिया

1. पेज में एक `पेपर-फू` तत्व डालें।
2. वेब ब्राउजर में पेज खोलें।
3. `पेपर-फू` तत्व पर क्लिक करें।
ब्राउज़रों की एक सूची जहां समस्या होती है। यदि सभी ब्राउज़रों में समस्या समान है तो इसे छोड़ दिया जा सकता है।
पुल अनुरोध सबमिट करना
पुल अनुरोध बनाने से पहले, कृपया सुनिश्चित करें कि पुल अनुरोध में संबंधित परिवर्तन के लिए एक मुद्दा मौजूद है जिसे आप बनाने का इरादा रखते हैं। यदि कोई समस्या मौजूद नहीं है, तो कृपया ऊपर दिए गए दिशानिर्देशों में से एक बनाएं। लक्ष्य एक पुल अनुरोध में गोता लगाने से पहले पॉलिमर लेखकों और समुदाय के साथ प्रस्तावित परिवर्तन के डिजाइन और आवश्यकता पर चर्चा करना है।

पुल अनुरोध सबमिट करते समय, कृपया प्रदान करें:

संबंधित समस्या या मुद्दों का संदर्भ जो पुल अनुरोध द्वारा बंद किया जाएगा। कृपया निम्नलिखित सिंटैक्स का उपयोग करके पुल अनुरोध विवरण में इन मुद्दों को देखें:
(किसी एक मुद्दे के लिए)
फिक्स # 20

(कई मुद्दों के लिए)
# 32 को ठीक करता है, # 40 को ठीक करता है
डिजाइन का एक संक्षिप्त विवरण किसी भी संबंधित मुद्दों को ठीक करने के लिए उपयोग किया जाता है। उदाहरण के लिए:
यह # 20 को उन शैलियों को हटाकर ठीक करता है जो लीक हो जाती हैं जो पृष्ठ को गुलाबी होने का कारण बनता है जब भी `पेपर-फ़ू` पर क्लिक किया जाता है।
प्रत्येक बग के लिए कम से कम एक परीक्षण तय किया गया है या पुल अनुरोध के हिस्से के रूप में जोड़ा गया है। बग को ठीक करने के अनुरोधों को खींचें या परीक्षण के साथ सुविधाओं को जोड़ने पर विचार नहीं किया जाएगा।
यदि किसी प्रस्तावित परिवर्तन में कई कमिट होते हैं, तो कृपया स्क्वाश को कम से कम उतना ही करें जितना कि परिवर्तन को व्यक्त करने के लिए आवश्यक है। पॉलिमर लेखक आपको स्क्वैश करने में मदद कर सकता है, इसलिए हमसे यह पूछने में डरें नहीं कि आपको इसकी मदद चाहिए!
