import matplotlib.pyplot as plt

# Sample data
categories = ['Category 1', 'Category 2', 'Category 3', 'Category 4', 'Category 5']
values = [23, 45, 56, 78, 33]

# Creating the column chart
plt.bar(categories, values, color='skyblue')

# Adding title and labels
plt.title('Sample Column Chart')
plt.xlabel('Categories')
plt.ylabel('Values')

# Displaying the chart
plt.show()
