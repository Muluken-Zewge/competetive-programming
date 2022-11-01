def gradingStudents(grades):
    new_grades = []
    for grade in range (0,len(grades)):
        next_multiple_of_5 = (grades[grade]//5+1)*5
        if grades[grade] < 38 :
            grades[grade] = grades[grade]
        elif next_multiple_of_5 - grades[grade] < 3:
            grades[grade] = next_multiple_of_5
        new_grades.append(grades[grade])
    return new_grades 
