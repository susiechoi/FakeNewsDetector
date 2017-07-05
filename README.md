# FakeNewsDetector
Returns a "fakeness" index rating the possibility of an article being fake news based on its headline
Created based on the fact that fake news articles on Facebook employ the clickbait-characteristic tactics of overused capitalization and unnecessary exclamation. This emotionalist presentation is indexed in the program.
Moving forward, this program will improve in the following ways:
- Create a way to scrape the title based on the inputed URL (rather than a manually-
    inputed title)
        -Pros: Allows index to also be based on the website host; less work 
            on the user's part
        - Difficulties: May be hard to generalize formatting rules across different
            news sources 
- Determine a statistically-significant metric for what is considered average
    capitalization in the title (currently, the informed placeholder value is 0.3, 
    viewable at line 31 of code) 
- Extend fake news index to actual article content, especially hitting grammatical
    errors --> Grammatical errors could be handled by a separate program 
