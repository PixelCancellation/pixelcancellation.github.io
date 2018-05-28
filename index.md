### Introduction 

I am an introduction. I will be written once the report is complete. I will be thoughtful, insightful, and less than 150 words. People will probably still skip me. I am so lonely. Nobody loves an introduction. 

Wait, I'm not even an introduction. I'm just the placeholder of an introduction - and I will definitely be deleted unless something goes terribly wrong. That's even worse! I'm just going to break down. Nobody will ever truly know me. I'm just a shame, waiting to be replaced. 
Congratulations, you just gave a piece of placeholder copy an existential crisis. 

You monster.


## Abstract

Live video streaming services are getting more and more popular in China. In order to ensure their own interests, various service providers have added visible watermarks, which have become increasingly fierce and vicious. Users (originators and viewers) are fed up with those ugly watermarks which are taking up more and more of the screen.

We have found that some of the service providers' watermarks can be actively eliminated, that is, originators can place a reverse watermark in their own video stream beforehand to cancel the service provider's watermark. Although the idea is intuitive, there are some problems in implementation, such as size, position, and shadow. After we theoretically provided an estimation of the achievable limits with computer graphics theory, we did a PoC against one of the largest video streaming service providers in China, which is also listed on the NYSE. The results were very good. After solving some problems related to the parameters related to color management and color space conversion, we can achieve nearly 100% active cancellation of watermarks.

To automate this process, we also build a ffmpeg filter as well as an OBS plugin, which can be helpful to do real-time adjusting with very short training sequence of frames during live broadcasting, so as to achieve a better watermark cancellation effect.

In addition, we propose several existential risks for watermarks that cannot be actively canceled: a) Transform Attack: to transform one watermark into another provider’s.  b) Code Rate Jitter Attack: adding high-frequency components to force video codec to reduce the code rate near watermark. c) Frame Squeezing Attack: sacrificing some resolution by squeezing screen, then restoring with user-defined javascript to bypass watermark. Corresponding examples and security countermeasures are also provided.
