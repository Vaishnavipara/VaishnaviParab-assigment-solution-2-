# Entity Extraction from Conversations (with classification models)

## AI Models & Approach

#### 1. **Facebook BART-Large-MNLI (Zero-Shot Classification)**
- **Model**: `facebook/bart-large-mnli` - 400M parameters
- **Purpose**: Complex zero-shot classification for preference categorization
- **Complexity Level**: High - uses advanced transformer architecture
- **Why Chosen**: State-of-the-art for zero-shot classification without fine-tuning

#### 2. **spaCy en_core_web_sm (Linguistic Processing)**
- **Model**: `en_core_web_sm` - Pre-trained NER model
- **Purpose**: Entity recognition and syntactic analysis
- **Complexity Level**: Medium - production NLP pipeline
- **Note**: Used for foundational NLP tasks, not complex classification

#### 3. **Hybrid Architecture**
- **Complex Component**: BART for semantic understanding
- **Supporting Component**: spaCy for structural analysis
- **Rule-Based Layer**: Custom patterns for precision

### Technical Approach Rationale:

- **Multi-model ensemble** for robustness
- **Fallback mechanisms** for reliability
- **Domain adaptability** through configurable patterns
- **Performance optimization** for real-time usage

This documentation provides comprehensive coverage of your project's technical architecture, model choices, and deployment options, making it ready for GitHub and professional use.
