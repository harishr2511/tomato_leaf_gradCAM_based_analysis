# tomato_leaf_gradCAM_based_analysis

In this research, we focused on developing an efficient and automated method for detecting and analyzing diseases in tomato leaves, specifically targeting Early Blight, Late Blight, and Septoria Leaf Spot. These diseases severely impact crop yield and quality, and traditional manual methods for disease identification are both time-consuming and error-prone. To address this, we leveraged convolutional neural networks (CNNs) like ResNet, DenseNet, and VGG, along with Gradient-weighted Class Activation Mapping (Grad-CAM), to classify diseases and quantify the affected leaf area. DenseNet201 stood out as the most effective model in our evaluations, offering high accuracy and robust performance. Additionally, Grad-CAM enabled us to visualize and highlight disease-specific patterns, which allowed us to assess the severity of the infections both quantitatively and visually.

<img width="457" alt="Screenshot 2025-01-17 at 9 41 09 PM" src="https://github.com/user-attachments/assets/a86fdecb-fa8a-4952-a74f-73090e589701" />


<img width="405" alt="Screenshot 2025-01-17 at 9 42 00 PM" src="https://github.com/user-attachments/assets/cc00bc35-8daa-4d44-a92b-185a6d009e3b" />

While working on this project, we noticed that certain diseases, like Early and Late Blight, often exhibit overlapping percentages of affected areas, making it challenging to differentiate between them. To overcome this, we relied on Grad-CAM heatmaps to pinpoint unique spatial patterns associated with each disease, improving our diagnostic capabilities. We also applied data augmentation techniques and fine-tuned the models to enhance performance and reduce overfitting, ensuring that our approach was scalable and effective across different conditions. This study reinforced the potential of combining advanced CNN architectures with Grad-CAM visualization to provide actionable insights for precision agriculture, helping farmers make timely and informed decisions for better crop management.

<img width="387" alt="Screenshot 2025-01-17 at 9 42 27 PM" src="https://github.com/user-attachments/assets/937a3716-1fc2-4886-848b-6b20fa6a2c30" />
