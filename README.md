def e_list(lst_=None):
    if lst_ is None:
        lst_ = []
    a = int(input("Enter length of the list:"))

    for x in range(a):
        member = input("Enter members of the list:")
        lst_.append(member)
    print(lst_)


e_list()
