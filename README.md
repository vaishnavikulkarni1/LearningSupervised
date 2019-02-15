# LearningSupervised
The title says it all. This is a machine learning based project. Our method uses semantic-enhanced Marginalized Denoising Auto-encoder (smSDA)  to detect bullying words.

14/02/2019

Objectives of the project:

Here we discuss the concept of a specialized representation learning
model for cyberbullying detection.

METHODOLOGY USED:

OSN System Construction Module

Construction of Bullying Feature Set

Cyberbullying Detection.

Semantic-Enhanced Marginalized Denoising Auto-Encoder.

15/2/2019

Literature Survey

Bullying is not a new phenomenon and cyberbullying has manifested itself as soon as digital technologies have become primary communication tools. On the positive side, social media like blogs, social networking sites (e.g. Facebook), and instant messaging platforms (e.g. WhatsApp) make it possible to communicate with anyone and at any time. Moreover, they are a place where people engage in social interaction, offering the possibility to establish new relationships and maintain existing friendships. On the negative side however, social media increase the risk of children being confronted with threatening situations including grooming or sexually transgressive behaviour, signals of depression and suicidal thoughts, and cyberbullying. Users are reachable 24/7 and are often able to remain anonymous if desired: this makes social media a convenient way for bullies to target their victims outside the school yard.

With regard to cyberbullying, a number of national and international initiatives have been launched over the past few years to increase children’s online safety. Examples include KiVa (http://www.kivaprogram.net/), a Finnish cyberbullying prevention programme, the ‘Non au harcèlement’ campaign in France, Belgian governmental initiatives and helplines (e.g. clicksafe.be, veiligonline.be, mediawijs.be) that provide information about online safety, and so on.

In spite of these efforts, a lot of undesirable and hurtful content remains online. Analysed a body of quantitative research on cyberbullying and observed cybervictimisation rates among teenagers between 20% and 40%. Focused on 12 to 17 year olds living in the United States and found that no less than 72% of them had encountered cyberbullying at least once within the year preceding the questionnaire.

The prevalence of cybervictimisation depends on the conceptualisation used in describing cyberbullying, but also on research variables such as location and the number and age span of the participants. Nevertheless, the above studies demonstrate that online platforms are increasingly used for bullying, which is a cause for concern given its impact. 

These findings demonstrate that cyberbullying is a serious problem the consequences of which can be dramatic. Early detection of cyberbullying attempts is therefore of key importance to youngsters’ mental well-being. Successful detection depends on effective monitoring of online content, but the amount of information on the Web makes it practically unfeasible for moderators to monitor all user-generated content manually. To tackle this problem, intelligent systems are required that process this information in a fast way and automatically signal potential threats. This way, moderators can respond quickly and prevent threatening situations from escalating. According to recent research, teenagers are generally in favour of such automatic monitoring, provided that effective follow-up strategies are formulated, and that privacy and autonomy are guaranteed.

Parental control tools (e.g. NetNanny, https://www.netnanny.com/) already block unsuited or undesirable content and some social networks make use of keyword-based moderation tools (i.e. using lists of profane and insulting words to flag harmful content). However, such approaches typically fail to detect implicit and subtle forms of cyberbullying in which no explicit vocabulary is used. This creates the need for intelligent and self-learning systems that go beyond keyword spotting and hence improve the recall of cyberbullying detection.

The ultimate goal of this type of research is to develop models that could improve manual monitoring for cyberbullying on social networks. We explore the automatic detection of textual signals of cyberbullying, in which cyberbulying is approached as a complex phenomenon that can be realised in various ways.

To tackle this problem, we propose a machine learning method based on a linear SVM classifier. Exploiting a rich feature set. The contribution we make is twofold: first, we develop a complex classifier to detect signals of cyberbullying, which allows us to detect different types of cyberbullying that are related to different social roles involved in a cyberbullying event. Second, we demonstrate that the methodology is easily portable to other languages, provided there is annotated data available, by performing experiments on English dataset.



The remainder of this paper is structured as follows:

the next section presents a definition of cyberbullying and its participant roles and provides an overview of the state of the art in cyberbullying detection. 

The Data collection and annotation section describes the corpus construction and annotation. 

Next, we present the experimental setup and discuss our experimental results for English. 

Finally, the Conclusion and future research section concludes this paper and provides some perspectives for further research.

