*/Input: Take marks obtained (out of 100) in each subject.
Calculate Total Marks: Sum up the marks obtained in all subjects.
Calculate Average Percentage: Divide the total marks by the total number of subjects to get the
average percentage.
Grade Calculation: Assign grades based on the average percentage achieved.
Display Results: Show the total marks, average percentage, and the corresponding grade to the user
*/
package GradeCalculator;
import java.util.Scanner;

public class StudentGradeCalculator {

	public static void main(String[] args) {
		int numberOfSubject = 3;
		int sumSubject = 0;
		int percentage;
		
		StudentGradeCalculator studentGradeCalculator = new StudentGradeCalculator();          
		Scanner sc = new Scanner(System.in);
		
		for(int i=0; i<numberOfSubject; i++) {
			System.out.println("Enter marks for Subject" + (i+1));
			sumSubject = sumSubject + sc.nextInt();
		}
		
		percentage = sumSubject / numberOfSubject;
		System.out.println("Sum of all subjects: "+sumSubject);
		System.out.println("Percentage: "+ percentage);
		
		if(percentage < 40) {
			System.out.println("Grade: Failed");
		} else if(percentage >= 40 && percentage < 60) {
			System.out.println("Grade: C");
		} else if(percentage >= 60 && percentage < 80) {
			System.out.println("Grade: B");
		} else if(percentage >= 80 && percentage <= 100){
			System.out.println("Grade: A");
		} else {
			System.out.println("Invalid Marks. Please enter valid marks.");
		}
	}
}
