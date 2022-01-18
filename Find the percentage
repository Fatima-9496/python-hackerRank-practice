if __name__ == '__main__':
    student_marks = {}
    sum=0.00
    data=[]
    for _ in range(int(input())):
        name, *line = input().split()
        scores = list(map(float, line))
        student_marks[name] = scores
    query_name = input()
    for i in student_marks:
        if query_name==i:
            data.extend(student_marks[i])
    for i in data:
        sum+=i
    print(format(sum/len(data),".2f"))
