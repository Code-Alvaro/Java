import java.util.ArrayList ;

public class Collec_1
 {
    public static void main(String[] args)
    {

        ArrayList<String> list =new ArrayList<>();
       // ArrayList<Integer> list1 =new ArrayList<>();

        list.add(0,"yamini");
        list.add(1,"Vaibhav");
        list.add(2,"Gaurav");
        list.add(3,"Aakash");
        list.add(4,"Rahul");
        list.add(5,"Eity");
        list.add(6,"Lallan");
        list.add(7,"Indra");
        list.add(8,"Sonu");
        list.add(9,"Tarun");

        /*
                list1.add(0,1);
                list1.add(2);
                list1.add(3);
                list1.add(4);
                list1.add(5);
                list1.add(6);
                list1.add(1,23);

                         list1.set(2,49);
                         System.out.println("->"+list);

                         System.out.println(list1);

                         int element = list1.get(2);

                         System.out.println(element);

                         list.remove(1);

                         System.out.println(list1.size());

                         System.out.println("->");
                         System.out.println("maximum number ->"+Collections.max(list1));
        */

        for (String str :list)
                   {
                       System.out.print(str+"\t"+str.length()+"\t");
                       StringBuffer br = new StringBuffer(str);
                      // StringBuffer f= br.reverse();
                       System.out.println(br.reverse());
                   }
                    System.out.println("---------------------");

    }
 }
