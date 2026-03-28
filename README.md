# european-churn-prediction
Loyiha nomi: European Bank Customer Churn Prediction
Maqsad: Supervised ML orqali mijozlarning bankdan ketishini bashorat qilish

## Warm-up Task 1 (28-mart)
Iris datasetda KNN bilan supervised classification pipeline yozdim. 
Test Accuracy: X.XXXX — bu pipeline ni churn loyihasida ham qo‘llayman.

## Warm-up Task 2 (28-mart)
make_classification bilan sun'iy datasetda Decision Tree max_depth 1-20 ni sinab ko'rdim.
Overfitting ~ depth=8-10 da boshlandi (train 100%, test pasaydi).
Bu bilimni european-churn-prediction loyihasida max_depth va min_samples_leaf bilan qo'llayman.

## Warm-up Task 3 (28-mart) — Probabilistic Thinking
Breast Cancer datasetda GaussianNB o'qitdim. Accuracy: X.XXXX
"Saraton bor" bashoratlarida 0.5 dan past ehtimollikdagi holat = 0 ta (chunki threshold 0.5).
Low-confidence (0.5-0.6) holatlar: XX ta — bu real hayotda qo'shimcha tekshiruv talab qiladi.
Insight: Deterministik predict emas, ehtimollikni ko'rib ishlatish kerak.