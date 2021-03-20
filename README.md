# Rostislav Telitsin
Hi,  

My name is **Rostislav Telitsin**  
I'm from Russia  
I'm 42  
I like coding. I'm working in the telecommunication industry and want to change occupation  

my email - *rostislav.telitsin@gmail.com*

## My portfolio 
The main aim of this portfolio is just to demonstrate my coding skills  
I hope it can help me to get a job of the software developer
### ![alt-Python](python-logo-glassy3.png "Python") [Python portfolio](Python_Poftfolio.github.io) 

I have some python experience. You can see it [here](Python_Poftfolio.github.io)  
Python is used to make a more simple routing work of my current job as far as in possible

### ![alt-Java](Java_logo2.png "Java") Java portfolio

#### [BabyCalc](https://github.com/RostislavTelitsin/babyCalc)

Simple calculator  
it implements the procedures of addition, subtraction, multiplication and division

- The example of a method to get data which user input:  
~~~
    private void getData () {
//trying to get data 1
        try {
            nnum1_meaning = Double.parseDouble(num1_frame.getText().toString());
//if getting data is impossible, variable = 0
        } catch (NumberFormatException e) {
            nnum1_meaning = (double) 0;
        }
//trying to get data 2
        try {
            nnum2_meaning = Double.parseDouble(num2_frame.getText().toString());
//if getting data is impossible, variable = 0
        } catch (NumberFormatException e) {
            nnum2_meaning = (double) 0;
        }
    }
~~~

- The other example is a method to calculate sum of two numbers:  
~~~
// if "+" pressed
    public void plusButtonClik (View v) {
        getData();
        result_meaning =nnum1_meaning + nnum2_meaning;
        result_frame.setText(Double.toString(result_meaning));
    }
~~~

#### [CheckIn/CheckOut Tool](https://github.com/RostislavTelitsin/CheckInOut.git)

This is android/java tool to implement CheckIn and CheckOut on site of my employer (when you start and finish your working day)

- the example of method to get data wich used input
~~~
some code
~~~

#### [Running tracker](https://github.com/RostislavTelitsin/runner.git)

simple calculator


~~~
some code
~~~


