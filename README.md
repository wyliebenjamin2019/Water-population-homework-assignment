# Water-population-homework-assignment
package com.company;

public class Main {

    public static void main(String[] args) {
	// write your code here
        double h1=72.0;
        double h2=19.8;
        double h3=50.0;
        double h4=67.0;
        double h5=16.0;
        double h6=53.0;
        double h7=69.0;
        double h8=30.0;
        double h9=52.0;
        double h10=40.0;
        double h11=31.0;
        double h12=75.0;
        double d1= 22.0;
        double d2= 18.0;
        double d3=13;
        double d4=16;
        double d5=14;
        double d6=23;
        double d7=22;
        double d8=22;
        double d9=23;
        double d10=16;
        double d11=18;
        double d12=23;
        double pop=37640;
        double waterperperson= 0.246;
        double days=28;
        double tvol1= 3.14*(d1/2)*(d1/2)*h1;
        double tvol2= 3.14*(d2/2)*(d2/2)*h2;
        double tvol3= 3.14*(d3/2)*(d3/2)*h3;
        double tvol4= 3.14*(d4/2)*(d4/2)*h4;
        double tvol5= 3.14*(d5/2)*(d5/2)*h5;
        double tvol6= 3.14*(d6/2)*(d6/2)*h6;
        double tvol7= 3.14*(d7/2)*(d7/2)*h7;
        double tvol8= 3.14*(d8/2)*(d8/2)*h8;
        double tvol9= 3.14*(d9/2)*(d9/2)*h9;
        double tvol10= 3.14*(d10/2)*(d10/2)*h10;
        double tvol11= 3.14*(d11/2)*(d11/2)*h11;
        double tvol12= 3.14*(d12/2)*(d12/2)*h12;
        double totalvolume= (tvol1)+(tvol2)+(tvol3)+(tvol4)+(tvol5)+(tvol6)+(tvol7)+(tvol8)+(tvol9)+(tvol10)+(tvol11)+(tvol12);
        double waterusedoneday= pop*waterperperson;
        double diff= totalvolume-(waterusedoneday*days);
        double finish1= -1*(diff/pop);
        double finish2= finish1/28;
        System.out.println("Each person must save,");
        System.out.println(finish2);
        System.out.println("cubic meters of water.");
    }
}
