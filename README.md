
# BioVerbNet: A large semantic-syntactic classification of verbs in biomedicine

This repository hosts the full BioVerbNet classification described in our [paper](https://jbiomedsem.biomedcentral.com/articles/10.1186/s13326-021-00247-z) Please cite it where appropriate.

## Abstract
### Background
Recent advances in representation learning have enabled large strides in natural language understanding; However, verbal reasoning remains a challenge for state-of-the-art systems. External sources of structured, expert-curated verb-related knowledge have been shown to boost model performance in different Natural Language Processing (NLP) tasks where accurate handling of verb meaning and behaviour is critical. The costliness and time required for manual lexicon construction has been a major obstacle to porting the benefits of such resources to NLP in specialised domains, such as biomedicine. To address this issue, we combine a neural classification method with expert annotation to create BioVerbNet. This new resource comprises 693 verbs assigned to 22 top-level and 117 fine-grained semantic-syntactic verb classes. We make this resource available complete with semantic roles and VerbNet-style syntactic frames.

### Results
We demonstrate the utility of the new resource in boosting model performance in document- and sentence-level classification in biomedicine. We apply an established retrofitting method to harness the verb class membership knowledge from BioVerbNet and transform a pretrained word embedding space by pulling together verbs belonging to the same semantic-syntactic class. The BioVerbNet knowledge-aware embeddings surpass the non-specialised baseline by a significant margin on both tasks.

### Conclusion
This work introduces the first large, annotated semantic-syntactic classification of biomedical verbs, providing a detailed account of the annotation process, the key differences in verb behaviour between the general and biomedical domain, and the design choices made to accurately capture the meaning and properties of verbs used in biomedical texts. The demonstrated benefits of leveraging BioVerbNet in text classification suggest the resource could help systems better tackle challenging NLP tasks in biomedicine.

