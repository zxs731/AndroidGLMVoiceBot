# GLM Voice Bot APP for Android

This sample demonstrates how to make speech on GLM4 with Java using the Speech SDK for Android.

## 替换下面的Azure语音TTS的key和region

* MainActivity.java
  
<code>private static final String SpeechSubscriptionKey = "xxx";
 private static final String SpeechRegion = "xxx";</code>


* ChatAPI.java 把下面的xxxx替换你的GLM key
  
<code>
    connection.setRequestProperty("Authorization", "Bearer xxxx"); 
</code>    
## References

* [Speech SDK API reference for Java](https://aka.ms/csspeech/javaref)
