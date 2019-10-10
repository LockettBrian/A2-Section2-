package Vechicle;

class Car {
  String nameS;
  String [] nameA;
  
  public void setName(String [] p1) {
  nameA = p1;
  }
  
  public void setName(String p2) {
  nameS = p2;
  }
}  

package Vechicle;

class Test{ 

  public static void main(String [] args) {

  String [] fA = {"11", "22"};
  String fS = "33 44";
  Car f1 = new Car();

  fl.setName(fA);
  f1.setName(fS);
  System.out.println("Print-1; " + fA[0] + "; " + f1.name[0]);

  Car [] f2 = new Car[2];
  f2[0] = f1;
  System.out.println("Print-2: " + f2[0].nameA[0] + "; " + f2[0].nameA[1]);

  f2[1].nameA[0] = f1.name[0];
  System.out.println("Print-3: " + f2[1].nameA[0]);

  f2[1] = f1;
  System.out.println('Print-4: " + f2[1].nameA[0]);
  }
}
