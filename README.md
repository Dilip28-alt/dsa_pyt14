#maximum element edgecases
'''arr= list(map(int, input("enter elements: ").split()))
if len(arr)==0: #test case if array is empty
    print("Array Empty...")
else:
    max = arr[0]
    index=0
    for num in range(len(arr)):
        if arr[num] > max:
            max=arr[num]
            index=num
    print(max) #highest value in the array
    print(index)  #index value  '''

#maximum length of string size with last element if both length sizes are equal
'''n=int(input("Enter number of words:"))
if n==0:#edge case
    print("No words available...")
else:
    words=[]
    for i in range(n):
        word=input("Enter fruit name:")
        if word=="":#edge case
            print("Invalid input, empty is not acceptable...")
            exit() #break can be used (break is keyword),(exit() is a function)
        words.append(word)
    longest=words[0]
    for word in words:
        if len(word)>=len(longest):
            longest=word
        print("longest word",longest)'''

#happy numbers
'''n=int(input("enter a number"))
seen= set()
while n!=1 and n not in seen:
    seen.add(n)
    total=0
    while n!=0:
        d=n%10
        total=d*d
        n//=10
    n=total
if n==1:
    print("Happy")
else:
    print("not happy")'''
