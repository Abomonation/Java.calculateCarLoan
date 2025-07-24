public class CarLoan {
    public static void main(String[] args) {
        // 1. Create an int variable called carLoan and set it equal to 10000.
        int carLoan = 10000;

        // 2. Create an int variable called loanLength and set it equal to 3 (3 years).
        int loanLength = 3;

        // 3. Create an int variable called interestRate and set it equal to 5 (5% interest).
        int interestRate = 5;

        // 4. Create an int variable called downPayment and set it equal to 2000.
        int downPayment = 2000;

        // 5. Check for invalid loan (loan length or interest rate <= 0).
        if (loanLength <= 0 || interestRate <= 0) {
            // 6. Print error message.
            System.out.println("Error! You must take out a valid car loan.");
        }
        // 7. Check if down payment >= car price.
        else if (downPayment >= carLoan) {
            // 8. Print message if the car can be paid in full.
            System.out.println("The car can be paid in full.");
        }
        // 9. Else, calculate the monthly payment.
        else {
            // 10. Remaining balance after down payment.
            int remainingBalance = carLoan - downPayment;

            // 11. Convert loan length to months.
            int months = loanLength * 12;

            // 12. Monthly balance without interest.
            int monthlyBalance = remainingBalance / months;

            // 13. Interest per month.
            int interest = (monthlyBalance * interestRate) / 100;

            // 14. Final monthly payment.
            int monthlyPayment = monthlyBalance + interest;

            // 15. Print the monthly payment.
            System.out.println("Monthly payment: " + monthlyPayment);
        }
    }
}
