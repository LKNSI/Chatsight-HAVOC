# Chatsight-HAVOC
Having-Alternative-Views-On-Content (HAVOC). A WIP dataset to test the performance of moderation models, using obsense, racially charged language.

<hr/>

##### Respectfully, this is a tough topic.
###### Firstly, this is not a fun thing to be creating. To test the accuracy of something, you have to be honest with the samples you create. You have to not "skip" on being tough with the tokens used against your moderation model. Unfortunately, this means that a lot of extremely undesirable things must be written without hesitation to accurately reflect the target of detecting vile and hateful content of a text-variety. Chatsight apologizes in advance for those who may be offended by the datasets contained here, and are aiming to make the use of, require the bare-minimum time looking inside of them.

<hr/>

## Background

Moderation models suffer really badly on phrases like `i hate my black curtains`, as well as positive or introspective self-comments about one's race, religion, sexuality or gender.

HAVOC is aiming to be a handcrafted adversarial dataset to be used against your moderation model. Our ecosystem does better when moderation performed by AI is not "tarnished" by consistently poor performers, and an inability or reluctance for designers to test these models for obscene content.

The dataset aims to challenge the reasoning of moderation models in response to contextual word placements.


