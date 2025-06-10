# CNN-Assignment-2025
NTCU113-2  ｜   Machine Learning   ｜   賴冠州教授
## Submission Requirements
- Submit your work as a Jupyter Notebook (.ipynb).
- File name format: `ClassNumber_CNN_Assignment.ipynb` (e.g., `ACS109145_CNN_Assignment.ipynb`).
- Ensure the notebook includes all code, visualizations, and a report section answering Task 5.
- Upload to this repository via a pull request (PR).
## Steps
1. Fork this repo.
2. Do Submission Requirements base on cnn_assignment.ipynb in colab.
3. attach your file(.ipynb) to your github repo
4. Commit and Create PR.
## **5 Key Tasks to Complete:**
1. **Task 1: Model Architecture Enhancement**
   - Modify the CNN model structure
   - Must include `model = models.Sequential` and `Conv2D` layers
   - **要求**：修改 CNN 模型架構
   - **檢查點**：模型必須包含至少一個 `model = models.Sequential` and `Conv2D` layers
   - **提示**：可以調整卷積層數量、濾波器數量、核大小等

2. **Task 2: Hyperparameter Optimization** 
   - Implement `model.compile` and `model.fit`
   - Specify optimizer (SGD/RMSprop/Adam)
   - **要求**：修改模型編譯時的超參數
   - **檢查點**：必須指定優化器（如 SGD、RMSprop、Adam）
   - **提示**：可以調整學習率、損失函數、優化器類型等

3. **Task 3: Data Augmentation**
   - Add `ImageDataGenerator` with augmentation parameters
   - Include: rotation_range, width_shift_range, height_shift_range, horizontal_flip
   - **要求**：實現數據增強技術
   - **檢查點**：使用 `ImageDataGenerator` 並包含增強參數
   - **提示**：可以使用旋轉、平移、翻轉等增強技術

4. **Task 4: Visualization**
   - Create plots using `plt.plot`, `plt.subplot`, or `plt.imshow`
   - Generate `predictions` variable for model predictions
   - **要求**：添加可視化功能
   - **檢查點**：
   - 包含繪圖代碼（`plt.plot`、`plt.imshow` 或 `plt.subplot`）
   - 必須包含模型預測代碼
   - **提示**：可以可視化訓練曲線、預測結果、混淆矩陣等

5. **Task 5: Report Section**
   - Add Markdown cell with heading containing "Task 5:", "Report", or "Conclusion"
   - Include meaningful analysis (more than 3 non-empty lines)
   - **要求**：撰寫實驗報告
   - **檢查點**：
   - 添加 Markdown 單元格，標題包含 "# Task 5:"、"# Report" 或 "# Conclusion"
   - 內容超過3行有意義的文字
   - **提示**：描述實驗過程、結果分析、改進建議等

## Autograding
- File name format validation
- Code execution without errors
- Presence of required code components
- Visualization outputs
- Report section completeness