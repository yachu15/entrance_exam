# Programming Basic Examination for OpenSpace Web3 Bootcamp

This is a simple test of programming and English skills. The questions that follow will evaluate your understanding of Linux commands and programming concepts.
Please answer the question with the Linux command, SQL query statement, and code.

Please follow your own understanding, do not use Google and ChatGPT.

Please fork this repository and answer the following five questions.

Q1: How to list all files, including hidden files, in the current directory using a Linux command?
Answer:ls -a

Q2: Rename 'world-hello.txt' to 'hello_world.md' using the Linux command.
Answer:mv world-hello.txt hello_world.md

Q3: How to request the latest code using Git command.
Answer:git pull

Q4: There is a MySQL table named `students` with columns `id`, `name`, `gender`, and `age`. Please write a SQL
query to retrieve male students who are older than 10 years old.
Answer:SELECT * FROM students WHERE gender = 'male' AND age > 10;

Q5: Please provide code to find the minimum number in an array using your preferred programming language.
Code: 
public class FindMinNumber {
    public static void main(String[] args) {
        int[] arr = {10, 15, 7, 25, 5};
        int min = arr[0];
        
        for (int i = 1; i < arr.length; i++) {
            if (arr[i] < min) {
                min = arr[i];
            }
        }
        
        System.out.println("The minimum number in the array is: " + min);
    }
}
