Hello-word
==========
/*
 * To change this template, choose Tools | Templates
 * and open the template in the editor.
 */

package singletonlogger;

/**
 *
 * @author ASUS
 */
public class Test {
    public static void main(String []args)
    {
    singleFactory f=new singleFactory();
    Logger l1=f.getLogger();
    try{
    l1.log("I am first logger");
        }catch(Exception e){System.out.println(e.toString());}

    
    Logger l2=f.getLogger();
    try{
    l2.log("I am second logger");
        }catch(Exception e){System.out.println(e.toString());}
    
System.out.println("get Msg from first Logger"+l1.getMsg());
System.out.println("get msg from second logger"+l2.getMsg());
    
    }

}
