# COSC140 lab 3

## Answers to the five questions at the end of the lab description

1.shark = Product(name= 'stuffed shark',description='soft, but with pointy teeth', price= 45.00, minimum_age_appropriate= 2,maximum_age_appropriate=43)
shark.save()

2. for p in Product.objects.all():
    print(p)
3. p= Product.objects.get(id='6')
p.price= 22.50
p.save()
4. p= Product.objects.get(id='6')
p.delete()
print(p.id)
id= None now 
5.objects = Product.objects.filter(name__icontains='e').filter(price__lt=10)

## Lab feedback

 * How long did you spend on this lab?

 * What did you think about it?  What was good?  What could be improved?

## Feedback

Once you commit and submit your work to Github, I'll update this section with feedback.

