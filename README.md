# Calculator-HW
 UPDATED USING INT
 Scanner scanner = new Scanner(System.in);
        System.out.println("Please enter two numbers :");

        double firstNumber = scanner.nextDouble();
        double secondNumber = scanner.nextDouble();

//        String option = scanner.nextLine();
//        System.out.println("Please enter one of the following +,-,*,/");

        System.out.print("Enter the operator you want(+, -, *, /) :");
        int option = scanner.nextInt();

        if (option == '+') {
            System.out.println(firstNumber + secondNumber);

        } else if (option == '-') {
            System.out.println(firstNumber - secondNumber);
        } else if (option == '*') {
            System.out.println(firstNumber * secondNumber);
        } else if (option == '/') {
            System.out.println(firstNumber / secondNumber);
        } else {
            System.out.println("Invalid entry");
        }

        System.out.print("Enter the operator you want again(+, -, *, /) :");
        int option2 = scanner.nextInt();
        if (option2 == '+') {
            System.out.println(firstNumber + secondNumber);

        } else if (option2 == '-') {
            System.out.println(firstNumber - secondNumber);
        } else if (option2 == '*') {
            System.out.println(firstNumber * secondNumber);
        } else if (option2 == '/') {
            System.out.println(firstNumber / secondNumber);
        } else {
            System.out.println("Invalid entry");
        }
    }
