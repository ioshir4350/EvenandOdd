# EvenandOdd
package com.company;

public class Main {


    public static void main(String[] args) {
        System.out.println(EvenandOdd("Isfar"));
        System.out.println(EvenandOdd("Oshir"));
    }

    public static String EvenandOdd (String str)
    {
     String outputodd = "";
     String outputeven= "";
     int io =1;
     int ie= 2;
     while (io < str.length())
     {
         outputodd = outputodd + str.substring(io);
         io = io +2;
     }
     while (ie < str.length())
     {
         outputeven = outputeven + str.substring (ie);
         ie = ie + 2;
     }
    return outputeven + outputodd;
    }
}
