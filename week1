import java.util.ArrayList;
import java.util.Scanner;

public class App 
{
  
    	int n=4; 
    	  
        
        class Data 
        { 
            int roll; 
            String name; 
            int marks; 
            long phone; 
            int size;
      
            
            Data(int roll, String name, int marks, long phone,int size) 
            { 
                this.roll = roll; 
                this.name = name; 
                this.marks = marks; 
                this.phone = phone; 
                this.size=size;
            } 
        } 
      
        public static void main(String args[]) 
        { 
           Scanner sc=new Scanner(System.in);
           int size;
           System.out.println("enter size : ");
            size =Integer.parseInt(sc.nextLine());
            int[] roll=new int[size];
            String[] name=new String[size];
            int[] marks=new int[size];
            long[] phone=new long[size];
            System.out.println("Enter "+size+" rollnos:");
            for(int i=0;i<size;i++) {
            	roll[i]=Integer.parseInt(sc.nextLine());
            }
            System.out.println("Enter "+size+" names:");
            for(int i=0;i<size;i++) {
            	name[i]=sc.nextLine();
            }
            System.out.println("Enter "+size+" marks:");
            for(int i=0;i<size;i++) {
            	marks[i]=Integer.parseInt(sc.nextLine());
            }
            System.out.println("Enter "+size+" phone numbers:");
            for(int i=0;i<size;i++) {
            	phone[i]=Long.parseLong(sc.nextLine());
            }
            App custom = new App(); 
      
           
            custom.addValues(roll, name, marks, phone,size); 
            sc.close();
        } 
      
        public void addValues(int roll[], String name[], int marks[], 
                              long phone[],int size) 
        { 
           
            ArrayList<Data> list=new ArrayList<>(); 
      
            for (int i = 0; i < size; i++) 
            { 
                
                list.add(new Data(roll[i], name[i], marks[i], phone[i], i)); 
            } 
      
            
            printValues(list,size); 
        } 
      
        public void printValues(ArrayList<Data> list,int size) 
        { 
        	System.out.println("Roll.no name marks phonenumber");
            for (int i = 0; i < size; i++) 
            { 
               
                Data data = list.get(i); 
      
                
                System.out.println(data.roll+"       "+data.name+"     "+data.marks+"       "+data.phone); 
            } 
        } 
    }
