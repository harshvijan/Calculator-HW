# Calculator-HW
 Create calculator
////
        Scanner scanner = new Scanner(System.in);
        System.out.println("Please enter two numbers :");

        double firstNumber = scanner.nextDouble();
        double secondNumber = scanner.nextDouble();



        System.out.print("Enter the operator you want(+, -, *, /) :");
        Character option = scanner.next().charAt(0);

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
        Character option2 = scanner.next().charAt(0);
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