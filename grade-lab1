def calculate_grade(scores):
    # ตรวจสอบว่าลิสต์ว่างหรือไม่ เพื่อป้องกัน ZeroDivisionError
    if not scores:
        return "N/A", 0

    total = 0
    # ย่อหน้าในลูป for
    for score in scores:
        total = total + score
    
    # คำนวณค่าเฉลี่ย
    average = total / len(scores)
    
    # ย่อหน้าใน if-elif-else เพื่อกำหนดเกรด
    if average >= 80:
        grade = "A"
    elif average >= 70:
        grade = "B"
    elif average >= 60:
        grade = "C"
    elif average >= 50:
        grade = "D"
    else:
        grade = "F"
    
    return grade, average

# การเรียกใช้งาน
scores = [85, 92, 78, 88, 95]
grade, avg = calculate_grade(scores)
print(f"เกรดที่ได้: {grade}, คะแนนเฉลี่ย: {avg}")

# ทดสอบกรณีลิสต์ว่าง
# print(calculate_grade([]))
