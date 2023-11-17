# java_assignments
//First Assignment 
/*
1)create a class "Shape" with 2 attributes, "width" and "height". Make sure one can not access these attributes directly.
provide accessor methods on these attributes and allow them to call from outside of your class.
*/
package package_name;
 public class Shape{
        private int width=41;
        private int height=51;
        
        public void getWidth(){
            System.out.println("the width is :" + width);
        }
    
        public void getHeight(){
            System.out.println("the Height is :" + height);
        }
    }
    public class First_assingment {
    public static void main(String[] args) {
    
        Shape obj = new Shape();
        obj.getWidth();
        obj.getHeight();
    }
}
