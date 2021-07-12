package com.company;

        public class Main {

            public static void main(String[] args) {
                // write your code here
                System.out.println("*(النتيجة حقي حق الترم الاول)*");
                System.out.println("------------------------------------");


                int a=100, b=62, c=75, d=92, e=61, f=83;

                System.out.println("الثقافة الاسلامية    "+a);
                System.out.println("اللغة العربية      "+b);
                System.out.println("الرياضيات          "+c);
                System.out.println( "اللغة الانجليزية    "+d);
                System.out.println("الرسم الهندسي       "+e);
                System.out.println("مقدمة في الحاسوب     "+f);

                System.out.println("----------------------------------");
                System.out.println(a+b+c+d+e+f+"  <----- المجموع");
                System.out.println("----------------------------------");
                System.out.println("78.83  <----- المعدل");

                int T = a+b+c+d+e+f/6;
                if (T > 90)

                    System.out.println(a+b+c+d+e+f+" ممتاز <----- التقدير");

                else if (T>80)

                    System.out.println(" جيد جدا <----- التقدير");
                else if (T>60)

                    System.out.println(" جيد <----- التقدير");

                else

                    System.out.println(" مقبول <----- التقدير");

                if (T > 50)


                    System.out.println(" ناجح <----- النتيجة");

                else


                    System.out.println(" راسب <----- النتيجة");



                System.out.println("*******************************************************");
                System.out.println("*     ملاحظة:  انا غشيت بحق المعدل ماعرفت كيف اطلعه    *");
                System.out.println("*******************************************************");




            }
        }


