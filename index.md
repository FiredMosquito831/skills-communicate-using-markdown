# Hello this is my test header

## This __BOLD__ *is a h2 header*

### This is a h3 header

#### This is a h4 header

##### This is a h5 header

###### This is a h6 header

##### This is how you print something in python


# This is a basic button that will redirect you to my transcription (English only). Please only do short English audio's less than 1 hour. If you refresh, you will lose progress.

<a href="https://7b76-2a02-2f09-d20e-6200-dd51-ebe4-274e-9871.ngrok-free.app/">
  <button>Test my ENGLISH transcription app (you can also do audio clearing and voice improvemnt DENOISING)</button>
</a>

# TEST IT NOW

#### Some random python code on how to print something

```python
print("This is some python code")

```
First|Second
-|-
1|2
Student|Alex Amadeus


#### Adding an image of my own transcription app

![Image of my app](https://cdn.discordapp.com/attachments/665903443998932992/1298737404584267867/image.png?ex=671aa6f6&is=67195576&hm=b276d9d015104491d46caf846d502415237be9507f7bec5f6a22bb29837bba83&)


#### Beyond the code I added before I will add some funny java code for a hangman game:

```java
package com.company;

import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        System.out.println("Hi");
        Scanner input = new Scanner(System.in);

        String name = input.nextLine();
        System.out.println(name);
        System.out.printf("\nHi, %s", name);

        // Create a Student object
        Student Denis = new Student("Denis", "Stoicescu", 20, 1.90f, "+40762523091", "ASE", "Economic Informatics", "Bucharest");

        // Print Student details
        System.out.printf("\nStudent:\nname: %s \nsurname: %s \nage: %d \nheight: %.2f \nphone number: %s \nuniversity: %s \nspecialization: %s \naddress: %s \nmail: %s",
                Denis.name, Denis.surname, Denis.age, Denis.height, Denis.phone_number, Denis.university, Denis.specialization, Denis.address, Denis.mail);
    }
}

class Student {
    // Fields for student attributes
    String name;
    String surname;
    int age;
    float height;
    String phone_number;
    String university;
    String specialization;
    String address;
    String mail;

    // Constructor for the Student class
    public Student(String name, String surname, int age, float height, String phone_number, String university, String specialization, String address) {
        // Assigning the passed parameters to the instance variables
        this.name = name;
        this.surname = surname;
        this.age = age;
        this.height = height;
        this.phone_number = phone_number;
        this.university = university;
        this.specialization = specialization;
        this.address = address;
        // Generating the email based on name and surname
        this.mail = String.format("%s.%s@stud.ase.ro".toLowerCase(), name.toLowerCase(), surname.toLowerCase());
    }
}
```
###### I wrote this for fun while at univ, cause i wondering of how student accounts and stuff is made on a site like the one from ASE



### TASKS
###### I have failed one of them today btw

- [ ] Train a proper ASR romanian model that works
- [X] Fail and spend 4 hours figuring it out with chatGPT for nothing cause I trained the wav2vec model wrong
- [X] Do the stuff from Microsoft Learn
- [X] Get super sick and lose a day of uni
- [X] Enjoy this fun and useful github couse 
