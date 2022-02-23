Burç Bulan Program

import java.util.Scanner;
public class Odev13 {

    public static void main(String[] args) {


        int month, day;
        Scanner input = new Scanner(System.in);

        String horoscope = "";
        boolean isError = false;


        System.out.print("Month of your birth: ");
        month = input.nextInt();


        // if - else ile
        if (month == 1) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 21) {
                    horoscope = "Capricorn";
                } else {
                    horoscope = "Aquarius";
                }
            } else {
                isError = true;
            }
        } else if (month == 2) {
            System.out.print("Day of your birth :  ");
            day = input.nextInt();
            if (day >= 1 && day <= 28) {
                if (day <= 19) {
                    horoscope = "Aquarius";
                } else {
                    horoscope = "Pisces";
                }
            } else {
                isError = true;
            }
        } else if (month == 3) {
            System.out.print("Day of your birth :  ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 20) {
                    horoscope = "Pisces";
                } else {
                    horoscope = "Aries";
                }
            } else {
                isError = true;
            }
        } else if (month == 4) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 30) {
                if (day <= 20) {
                    horoscope = "Aries";
                } else {
                    horoscope = "Taurus";
                }
            } else {
                isError= true;
            }
        } else if (month == 5) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 21) {
                    horoscope = "Taurus";
                } else {
                    horoscope = "Gemini";
                }
            } else {
                isError = true;
            }
        } else if (month == 6) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 30) {
                if (day <= 22) {
                    horoscope = "Gemini";
                } else {
                    horoscope = "Cancer";
                }
            } else {
                isError = true;
            }
        } else if (month == 7) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 22) {
                    horoscope = "Cancer";
                } else {
                    horoscope = "Leo";
                }
            } else {
                isError = true;
            }
        } else if (month == 8) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 22) {
                    horoscope = "Leo";
                } else {
                    horoscope = "Virgo";
                }
            } else {
                isError = true;
            }
        } else if (month == 9) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 30) {
                if (day <= 22) {
                    horoscope = "Virgo";
                } else {
                    horoscope = "Libra";
                }
            } else {
                isError = true;
            }
        } else if (month == 10) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 22) {
                    horoscope = "Libra";
                } else {
                    horoscope = "Scorpio";
                }
            } else {
                isError = true;
            }
        } else if (month == 11) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 30) {
                if (day <= 21) {
                    horoscope = "Scorpio";
                } else {
                    horoscope = "Sagittarius";
                }
            } else {
                isError = true;
            }
        } else if (month == 12) {
            System.out.print("Day of your birth : ");
            day = input.nextInt();
            if (day >= 1 && day <= 31) {
                if (day <= 21) {
                    horoscope = "Sagittarius";
                } else {
                    horoscope = "Capricorn";
                }
            } else {
                isError =true;
            }
        } else {
            isError = true;
        }

        if (isError){
            System.out.println("Invalid. Please try again! ");
        }else {
            System.out.println("Your horoscope " +horoscope);
        }




    }

}

