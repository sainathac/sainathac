# Projects

This page expands on my public portfolio projects and professional automation work. Company-related automation work is described in a sanitized way to avoid exposing client names, internal systems, private workflow labels, real data, or implementation details.

## Professional Automation Work

### AI Email Triage & RPA Automation

**Timeline:** Sep 11, 2025 - Apr 24, 2026  
**Status:** Completed  
**Role:** End-to-end owner across planning, development, testing, launch, production support, and debugging

Built an AI-assisted RPA automation workflow for finance inbox operations. The project focused on reducing manual handling of recurring finance emails by using automated classification, routing, inquiry handling, response generation, and exception management.

#### Public-safe highlights

- Designed and developed a workflow to read, classify, route, and process finance-related emails.
- Automated payment inquiry handling using email parsing, invoice-reference extraction, system-status validation, and response generation.
- Built routing logic for operational categories such as payment inquiries, invoice submissions, vendor statements, system issues, and exception cases.
- Implemented exception routing for ambiguous or unmatched emails to support human review.
- Added completed-item archiving to support tracking, audit visibility, and operational review.
- Defined and executed testing criteria for routing accuracy and automated-response quality before rollout.
- Delivered the system independently from scratch across the full project lifecycle.

#### Skills demonstrated

- RPA workflow design
- Python automation
- LLM-assisted classification
- Email parsing and routing
- API integration patterns
- SQL/data validation concepts
- Exception handling
- Testing and production rollout
- Operational documentation

#### Not publicly shared

Client names, internal project names, real email addresses, exact folder names, vendor reply templates, screenshots, private workflow diagrams, system credentials, sample invoices, production data, and internal approval documents are intentionally excluded.

## Financial Reconciliation & Report Automation

**Timeline:** Apr 25, 2026 - Present  
**Status:** In development  
**Role:** Automation design and development

Currently developing a finance automation pipeline for recurring report processing, CSV ingestion, reconciliation preparation, accounting-code mapping, and ERP-ready upload workflows.

#### Public-safe highlights

- Designing automation workflows for report extraction, CSV intake, data cleansing, validation, transformation, and upload preparation.
- Translating recurring manual finance operations into structured, repeatable automation requirements.
- Building toward improved consistency, timeliness, and auditability across recurring financial reporting workflows.
- Working with workflow components involving shared-drive file handling, spreadsheet automation, email/archive handling, accounting mappings, and ERP-compatible formatting.
- Documenting assumptions, exclusions, and operational boundaries to keep automation aligned with production finance needs.

#### Skills demonstrated

- Financial data automation
- CSV and spreadsheet processing
- Python-driven Excel automation
- Data cleansing and transformation
- Reconciliation workflow design
- Accounting-code mapping concepts
- ERP-ready formatting
- Automation scope documentation

#### Not publicly shared

Client names, exact report names, vendor names, exact volumes, frequencies, effort estimates, GL mapping rules, validation rules, upload formats, screenshots, private paths, and production financial data are intentionally excluded.

## Academic & Portfolio Projects

### Netflix-style Recommendation Engine

Developed a personalized movie recommendation system using user-item rating data and genre metadata.

#### Highlights

- Performed exploratory data analysis using Python.
- Built user-item rating matrices and engineered useful recommendation features.
- Implemented collaborative filtering and content-based filtering.
- Generated top-K movie recommendations.
- Evaluated model performance using RMSE and ranking metrics.

#### Skills demonstrated

- Python
- Pandas
- NumPy
- Data analysis
- Feature engineering
- Recommendation systems
- Model evaluation

### Smart Drug Dispensing System Using ESP32

Designed and implemented an IoT-enabled automated drug dispensing system using ESP32 for scheduled and on-demand medication delivery.

#### Highlights

- Integrated RTC-based scheduling for time-based dispensing.
- Used stepper motor-controlled compartments for automated medication release.
- Added multi-sensory alert mechanisms.
- Engineered fail-safe features including dispensing validation and battery backup.
- Presented at the International Conference on Inventive Computation Technologies, ICICT 2025, and published in IEEE.

#### Skills demonstrated

- ESP32
- Embedded systems
- IoT design
- RTC scheduling
- Stepper motor control
- Hardware validation
- Reliability-focused system design

## Deep Learning Lab Series

This series contains cleaned TensorFlow/Keras learning labs published as separate repositories. They are structured as public educational projects rather than raw course assignment dumps.

### Neural Network From Scratch

Repository: https://github.com/sainathac/neural-network-from-scratch

- Demonstrates feed-forward prediction, squared error, manual gradient calculation, and weight updates.
- Uses a tiny two-input regression example to explain neural network fundamentals step by step.
- Includes error and prediction progression plots across epochs.

### MNIST Digit Classifier

Repository: https://github.com/sainathac/mnist-digit-classifier

- Trains a dense TensorFlow/Keras neural network on the MNIST handwritten digit dataset.
- Covers normalization, one-hot encoding, training, evaluation, prediction, and training/validation plots.
- Serves as a clean entry point into image classification with dense networks.

### Fashion-MNIST Model Lifecycle

Repository: https://github.com/sainathac/fashion-mnist-model-lifecycle

- Trains a dense classifier on Fashion-MNIST and demonstrates a basic model lifecycle workflow.
- Includes sample visualization, TensorBoard logging, evaluation, model saving, model loading, and parameter verification.
- Highlights practical model management beyond raw training.

### Cats vs Dogs CNN Classifier

Repository: https://github.com/sainathac/cats-vs-dogs-cnn-classifier

- Builds a convolutional neural network from scratch for cat and dog image classification.
- Uses image augmentation, convolution/max-pooling blocks, and validation-based evaluation.
- Demonstrates core computer vision workflow design in TensorFlow/Keras.

### VGG16 Transfer Learning Classifier

Repository: https://github.com/sainathac/vgg16-transfer-learning-classifier

- Applies transfer learning with VGG16 pretrained on ImageNet for cats vs dogs classification.
- Uses a frozen convolutional base with a custom dense classifier head and dropout regularization.
- Demonstrates how pretrained visual features can accelerate image classification tasks.

### IMDB Sentiment RNN

Repository: https://github.com/sainathac/imdb-sentiment-rnn

- Trains a SimpleRNN-based sentiment classifier on the Keras IMDB review dataset.
- Covers vocabulary limiting, sequence padding, embeddings, validation, and test evaluation.
- Serves as a baseline NLP deep learning project for sequence modeling and sentiment analysis.
