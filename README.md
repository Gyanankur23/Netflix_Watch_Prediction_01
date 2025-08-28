#  Netflix Watch Prediction – CaseCraft Analytics Project Sprint Project 1

## 🔍 Overview  
This project simulates a Netflix-style recommendation scenario, focusing on user watch behavior across genres, time slots, and devices. It blends exploratory data analysis with predictive modeling to estimate content liking, offering a hands-on dive into consumer analytics.

## 🎯 Objective  
To analyze and model user watch behavior using genre preferences, time of day, and device usage. The goal is to uncover engagement patterns and build a logistic regression model to predict whether a user liked the content.

## 📊 Dataset Summary  
- `user_id`: Unique identifier  
- `genre`: Type of content watched  
- `watch_time`: Time slot (Morning, Afternoon, Evening, Night)  
- `device`: Viewing device (Mobile, TV, Laptop, Tablet)  
- `duration_minutes`: Total watch time  
- `liked`: Binary flag (1 = liked, 0 = not liked)

## 📈 Visual Explorations  
- Genre popularity distribution  
- Average watch duration by genre  
- Device usage across time slots  
- Liked vs not liked content by genre  
- Heatmap of genre-device engagement  
- Boxplot of watch duration by time of day

## 🤖 Predictive Modeling  
- **Model**: Logistic Regression  
- **Features**: Genre, watch_time, device (OneHotEncoded)  
- **Performance**:  
  - Accuracy: 57%  
  - Precision (Liked): 0.58  
  - Recall (Liked): 0.97  
  - F1-score (Liked): 0.72

## 🧠 Key Insights  
1. **Genre Engagement**: Drama and Documentary drive deeper watch durations.  
2. **Device Patterns**: Mobile dominates daytime; TV and laptops peak in evenings.  
3. **Content Liking**: Thrillers and Documentaries are most liked.  
4. **Device-Genre Match**: Drama and Thriller preferred on TV; Comedy on mobile.  
5. **Time-Based Duration**: Evening sessions show longest engagement.  
6. **Model Utility**: Genre, device, and time of day are useful predictors, though nonlinear models may improve accuracy.

## ✅ Final Conclusion  
The Netflix Watch Prediction dashboard offers a clarity-first framework for understanding viewer behavior and content engagement. By combining genre, device, and time-of-day features, it uncovers actionable patterns in watch duration and content liking. While the logistic regression model provides a strong baseline—especially with high recall—future iterations could benefit from nonlinear models to capture deeper behavioral nuances.

This project balances strategic insight with modular design, making it ideal for deployment in recommendation systems, viewer segmentation, and content strategy. Its reproducible structure and visual storytelling make it a strong candidate for portfolio inclusion and cross-platform adaptation.