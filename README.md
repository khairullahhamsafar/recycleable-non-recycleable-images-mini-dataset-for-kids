# Recyclable vs Organic Waste Images Mini Dataset for Kids

A small, kid-friendly image dataset designed for teaching machine learning, computer vision, and waste classification concepts to children and beginners.

This dataset helps students train an AI model to distinguish between recyclable and organic waste by recognizing visual patterns in images. It is ideal for hands-on classroom activities that demonstrate how AI can contribute to environmental sustainability.

## 📁 Dataset Structure

```text
Recycleable_Non_Recycleable_Images_Mini_Dataset_For_Kids/
├── TRAIN/
│   ├── recycleable/    # 300 training images
│   └── organic/        # 300 training images
└── TEST/
    ├── recycleable/    # 5 testing images
    └── organic/        # 5 testing images
```

### Classes

- `recycleable`
- `organic`

## 🎯 Purpose

This dataset is perfect for:

- Teaching machine learning to kids
- Introduction to computer vision
- Waste classification projects
- Learning about pattern recognition
- AI for environmental sustainability
- STEM and AI classroom activities
- Hands-on image classification projects

## 📊 Details

| Attribute | Value |
|-----------|---------|
| Classes | 2 (recycleable, organic) |
| Training images per class | 300 |
| Total training images | 600 |
| Testing images per class | 5 |
| Total testing images | 10 |
| Total images | 610 |
| Dataset size | Mini/small |
| Source | Compiled from publicly available waste image datasets |

## 🌍 Learning Objective

Using this dataset, students can:

1. Train a simple image classification model.
2. Learn how AI identifies visual patterns.
3. Understand supervised machine learning.
4. Discover how AI can help solve environmental challenges.
5. Test model performance using unseen images.
6. Learn why separate training and testing datasets are important.

## 🚀 Quick Start

```python
from pathlib import Path

dataset_dir = Path("Recycleable_Non_Recycleable_Images_Mini_Dataset_For_Kids")

for split in ["TRAIN", "TEST"]:
    split_dir = dataset_dir / split
    print(f"\n{split}")

    for class_dir in split_dir.iterdir():
        if class_dir.is_dir():
            print(
                f"{class_dir.name}: "
                f"{len(list(class_dir.glob('*')))} images"
            )
```

## 🤖 Suggested Classroom Activity

**Project:** *Train a virtual bot to distinguish between recyclable waste and organic trash.*

Students will:

1. Train an AI model using the images in the `TRAIN` folder.
2. Test the model using the images in the `TEST` folder.
3. Observe how the AI predicts each waste category.
4. Explore how computers recognize patterns in everyday objects.
5. Discuss how AI-powered recycling systems can help protect the environment.

Questions for students:

- What visual clues help the AI identify recyclable items?
- How is organic waste different from recyclable waste?
- Why is a testing dataset important?
- How would collecting more images improve the model?
- Where might this technology be used in real life?

## ⚠️ Notes

- Images were collected and prepared from publicly available waste image datasets.
- Intended for educational purposes and beginner AI/ML projects.
- Designed for teaching image classification and pattern recognition concepts.
- Small size enables quick experimentation on local machines.
- Suitable for classroom demonstrations and guided learning activities.

## 📝 License

Public dataset for educational use.

## 🙏 Acknowledgments

The images in this mini dataset were selected from larger publicly available waste classification datasets. Credit belongs to the original dataset creators and contributors.

## 🔍 Keywords

Machine Learning for Kids, AI for Kids, Computer Vision Dataset, Waste Classification, Recyclable Waste Detection, Organic Waste Classification, Smart Recycling, Environmental AI, Green AI, Sustainability, Image Classification Dataset, Educational Dataset, Beginner Machine Learning Dataset, Pattern Recognition, Prediction Models, Supervised Learning, STEM Education, Classroom AI Activities, Mini Dataset, Small Dataset

## 🏷️ Topics

#MachineLearning #ArtificialIntelligence #ComputerVision
#WasteClassification #RecyclingAI
#EnvironmentalAI #GreenAI
#ImageClassification #PatternRecognition
#MachineLearningForKids #AIForKids
#EducationalDataset #STEMEducation
#Sustainability #ComputerVisionDataset
#SupervisedLearning #MiniDataset
#DataScienceEducation #Recycling

## 👨‍💻 Author

Prepared and curated by **Khairullah Hamsafar** for educational and classroom learning purposes.

Focused on making Machine Learning, Artificial Intelligence, Computer Vision, Data Science, and Generative AI accessible to children, students, educators, and beginners.
