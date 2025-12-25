# Random Forest – תשובות
---

האם מודל Random Forest פותר בעיית קלסיפיקציה, רגרסיה או גם וגם?

**תשובה:**  
גם וגם (קלסיפיקציה וגם רגרסיה).

---

מהו הרעיון המרכזי שעליו מבוסס מודל Random Forest?

כיצד Random Forest קשור למודל Decision Tree?

**תשובה:**  
זה אוסף של הרבה עצי החלטה. כל עץ נותן תחזית, ובסוף מאחדים את התוצאות. Random Forest בנוי על Decision Trees, רק מרבים עצים ומכניסים אקראיות.

---

מהו Bootstrap Sampling וכיצד הוא משמש ב־Random Forest?

**תשובה:**  
דגימה אקראית עם החזרה מהדאטה כדי לבנות לכל עץ סט אימון קצת שונה.

---

מדוע השימוש באקראיות משפר את ביצועי המודל?

**תשובה:**  
כי הוא גורם לעצים להיות שונים אחד מהשני, מפחית Overfitting.

---

כיצד מתקבלת התחזית הסופית ב־Random Forest לקלסיפיקציה?

מהו מנגנון ההצבעה (Voting) ב־Random Forest וכיצד הוא פועל?

**תשובה:**  
כל עץ “מצביע” למחלקה. המחלקה עם הכי הרבה קולות היא התחזית הסופית.

---

כיצד מתקבלת התחזית הסופית ב־Random Forest לרגרסיה?

**תשובה:**  
מחשבים ממוצע של התחזיות המספריות מכל העצים.

---

אילו Hyperparameters נפוצים קיימים במודל Random Forest?

**תשובה:**  
n_estimators, max_depth, min_samples_split, min_samples_leaf, max_features, bootstrap.

---

מהו OOB Error (Out-Of-Bag Error) וכיצד משתמשים בו להערכת ביצועי המודל?

**תשובה:**  
בכל עץ יש דוגמאות שלא נבחרו ב־Bootstrap (Out-of-bag).

---

מה היתרון של Random Forest מבחינת יציבות המודל לעומת Decision Tree?

**תשובה:**  
הרבה עצים ביחד פחות רגישים לשינוי קטן בדאטה, ולכן המודל יציב יותר ופחות נוטה ל־Overfitting מעץ בודד.

---

אילו מדדי ביצוע מתאימים להערכת מודל Random Forest בקלסיפיקציה וברגרסיה?

**תשובה:**  
בקלסיפיקציה: Accuracy, Precision, Recall, F1, Confusion Matrix.  
ברגרסיה: MSE, RMSE, MAE, R².

---

יש לשלוח את הפתרון למייל:
📧 [pythonai200425+supfinal@gmail.com](mailto:pythonai200425+supfinal@gmail.com)

---
