# Where-Am-I-
N= int(input("Enter number of farms"))
while N <1 or N>100:
    print("Try again")
    N = int(input("Enter number of farms"))

sequence=str(input("Enter the sequence of mailboxes"))

for counter in range(1, N):
    sequence.split()
    firstletter=sequence[0]
    if firstletter == sequence[counter]:
        distancebetween = counter
        print(counter)
