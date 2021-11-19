~ \\תיקית הבית של היוזר 
cd /var/www
cd ~
cd - \\ מחזיר אותי למקום הקודם בו הייתי

cd . \\ התיקייה הנוכחית - שימושי לקבצים
cd .. \\ תיקייה אחת למעלה

Tab - השלמה אוטומטית מתוך חלקי הפקודה
clear - ניקיון הלוח

גלגל עכבר - העתקת קבצים מהירה בטרמינל
cd ~
mkdir folder1
mv folder1 /tmp
cd tmp
mv folder1 new_folder \\ כאשר זה באותו מיקום פקודת מו משנה שם
cp העתקה
cp file new_file
cp file /var/www/

rm -r  <folder> \\ רקורסיב למחוק את כל הקבצים
לא להשתמש ב F \\ FORCE
לא להשתמש ב \
rm -rf \ \\מחיקת כל הקבצים מהמחשב

whoami \\ משתמש להבנת המשתמש הנוכחי נוח במיוחד במצב SSH 
history - \\ לחפש סיסמאות ביוזרים שלא מחקו היסטוריה
clear - ctrl l
passwd - שינוי סיסמה לא להשתמש ב
root toor
passwd -d \\ יצירת משתמש ללא סיסמה

wc - ספירת מילים

cat /etc/passwd
cut -d ":" -f 1,2,3 /etc/passwd

crunch 1 5 1234567890 -o pass.lst \\ מכין קובץ לפריצה