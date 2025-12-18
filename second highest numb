if __name__ == '__main__':
    
  students = []
  scores= []
  for _ in range(int(input())):
        name = input()
        score = float(input())
  students.append([name, score])
  scores.append(score)
       
  unique_scores = sorted(set(scores))
  second_lowest = unique_scores[1]
  
  
  
  result = [students[0] for students in students if students[1]==second_lowest]
  
  result.sort()
  
  for name in result:
    print(name)     
