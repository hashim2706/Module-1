# Experiment No: 1e – SEB-Minimum of Three Numbers

## AIM  
Write a  python program to determine traffic status based on the fraction of roadways covered.
The variable traffic_fraction
>0.5 high traffic
>0.25 and <=0.5 medium traffic
<0.25 Low Traffic 

## ALGORITHM  
1.Start
2.Input the value of traffic_fraction
3.If traffic_fraction > 0.5
4.Set traffic_status to "High Traffic"
5.Else if traffic_fraction > 0.25 and traffic_fraction <= 0.5
6.Set traffic_status to "Medium Traffic"
7.Else
8.Set traffic_status to "Low Traffic"
9.Output the traffic_status
10.End
## PROGRAM
```python
a=float(input())
if(a>0.5):
    print("High Traffic!")
elif(a>0.5 and a<=0.25):
        print("medium traffic")
elif(a<0.25):
        print("Low Traffic")
else:
    print("Medium Traffic")
```

## OUTPUT

![Screenshot (188)](https://github.com/user-attachments/assets/87862197-c4a3-44ba-8977-42d1d67ba278)


## RESULT
Thus , the program to determine traffic status based on the fraction of roadways covered was implemented and executed successfully.
