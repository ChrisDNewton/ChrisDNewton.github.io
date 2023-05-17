---
title: This is a test page to check search terms are being picked up by webscraper
---

**Test page for webscraping script checks**

* Certification Council for Professional Dog Trainers
* CCPDT
* international association of animal behavior consultants
* IASBC
* IACP
* International Association of Canine Professionals

* Positive reinforcement, positive training, positively reinforcing
* Pack, but not package or packages
* Alpha, but not alphanumeric 
* Dog whisperer, but not hotdog whisperer
* Balanced training or balanced trainers but not new balance trainers.

```python
    positive_training_technique_words = len(re.findall(r"positive training technique", text.lower()))
    positive_training_words = len(re.findall(r"positive training", text.lower()))
    correction_words = len(re.findall(r"correction", text.lower()))
    science_words = len(re.findall(r"science", text.lower()))
    aggression_words = len(re.findall(r"aggression", text.lower()))
    aggressive_dog_words = len(re.findall(r"aggressive dog", text.lower()))
    aggressive_behavior_words = len(re.findall(r"aggressive behavior", text.lower()))
    top_dog_words = len(re.findall(r"\btop dog", text.lower()))
    pack_leader_words = len(re.findall(r"\bpack leader", text.lower()))
    leader_of_your_pack_words = len(re.findall(r"leader of your pack", text.lower()))
    dogs_leader_words = len(re.findall(r"dog's leader.+", text.lower())) # apostrophe - test this
    pack_structure_words = len(re.findall(r"pack structure", text.lower()))
    natural_words_words = len(re.findall(r"nature’s design|mother nature|"
                                         r"innate ability|natural|dog intuitive|"
                                         r"vibe|sense|natural|natural instincts", text.lower()))
```

[Back to main page](https://chrisdnewton.github.io/)


