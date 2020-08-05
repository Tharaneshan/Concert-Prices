# Concert-Prices
Shows prices for different seat numbers at a concert.

    import java.util.Scanner;
    public class Concert {
    public static void main(String[] args) {
      int seatNum;
      Scanner input = new Scanner(System.in);

      System.out.println("Enter your seat number: ");
      seatNum = input.nextInt();
      input.close();

      if ((seatNum >= 100) && (seatNum <= 159)) {
        System.out.println("Section A and Ticket price is $150");
      } else if ((seatNum>=160) && (seatNum<=199)) {
           System.out.println("Section B and Ticket price is $125");
         } else if ((seatNum >= 200) && (seatNum <= 259)) {
              System.out.println("Section C and Ticket price is $100");
            } else if ((seatNum >= 260) && (seatNum <= 299)) {
                 System.out.println("Section D and Ticket price is $90");
               } else if ((seatNum >= 300) && (seatNum <= 325)) {
                    System.out.println("Section E and Ticket price is $75");
                  } else if ((seatNum >= 326) && (seatNum <= 349)) {
                       System.out.println("Section F and Ticket price is $60");
                     } else if ((seatNum >= 350) && (seatNum <= 399)) {
                          System.out.println("Section G and Ticket price is $50");
                        } else if ((seatNum >= 400) && (seatNum <= 459)) {
                             System.out.println("Section H and Ticket price is $40");
                           } else if ((seatNum >= 460) && (seatNum <= 499)) {
                                System.out.println("Section I and Ticket price is $25");
                              } else {
                                System.out.println("Sorry its not a Seat number");
                              }
                           }
                        }
