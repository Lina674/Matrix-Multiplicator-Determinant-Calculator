using System;
using System.Numerics;

class Program {
  public static void Main (string[] args) {
   
    
    Console.WriteLine("Multiplication or Determinant (m/d)?\n");
    string choice=Console.ReadLine();
   
    if (choice=="m"){
    Console.Write("Dimension: ");
    int input=Convert.ToInt32(Console.ReadLine());
    
    Console.WriteLine("\n");

    int square = input*input;
    double [] m1=new double[square];
    double [] m2=new double[square];
    double e3;

    for (int i=0; i<square; i++) {
      double e1=Convert.ToDouble(Console.ReadLine());
      m1[i]=e1;
    }
    Console.WriteLine("\n");

    for (int k=0; k<square; k++) {
      double e2=Convert.ToDouble(Console.ReadLine());
      m2[k]=e2;
    }
    
    double [] m3=new double[square];
    
    if (input==2) {
    e3=(m1[0]*m2[0])+(m1[1]*m2[2]);
        m3[0]=e3;
   
    e3=(m1[0]*m2[1])+(m1[1]*m2[3]);
        m3[1]=e3;
   
    e3=(m1[2]*m2[0])+(m1[3]*m2[2]);
        m3[2]=e3;

    e3=(m1[2]*m2[1])+(m1[3]*m2[3]);
        m3[3]=e3;
    
    for (int m=0; m<square; m++) {
  Console.WriteLine("\n"+ m3[m]);
    }
    }

    if (input==3) {
    e3=(m1[0]*m2[0])+(m1[1]*m2[3])+(m1[2]*m2[6]);
        m3[0]=e3;
   
    e3=(m1[0]*m2[1])+(m1[1]*m2[4])+(m1[2]*m2[7]);
        m3[1]=e3;
   
    e3=(m1[0]*m2[2])+(m1[1]*m2[5])+(m1[2]*m2[8]);
        m3[2]=e3;

    e3=(m1[3]*m2[0])+(m1[4]*m2[3])+(m1[5]*m2[6]);
        m3[3]=e3;
    
    e3=(m1[3]*m2[1])+(m1[4]*m2[4])+(m1[5]*m2[7]);
        m3[4]=e3;
    
    e3=(m1[3]*m2[2])+(m1[4]*m2[5])+(m1[5]*m2[8]);
        m3[5]=e3;

    e3=(m1[6]*m2[0])+(m1[7]*m2[3])+(m1[8]*m2[6]);
        m3[6]=e3;

    e3=(m1[6]*m2[1])+(m1[7]*m2[4])+(m1[8]*m2[7]);
        m3[7]=e3;

    e3=(m1[6]*m2[2])+(m1[7]*m2[5])+(m1[8]*m2[8]);
        m3[8]=e3;
       
        for (int m=0; m<square; m++) {
        Console.WriteLine("\n"+ m3[m]);
        }
}

    if (input==4) {
    e3=(m1[0]*m2[0])+(m1[1]*m2[4])+(m1[2]*m2[8]+(m1[3]*m2[12]));
        m3[0]=e3;
   
    e3=(m1[0]*m2[1])+(m1[1]*m2[5])+(m1[2]*m2[9])+(m1[3]*m2[13]);
        m3[1]=e3;
   
    e3=(m1[0]*m2[2])+(m1[1]*m2[6])+(m1[2]*m2[10])+(m1[3]*m2[14]);
        m3[2]=e3;

    e3=(m1[0]*m2[3])+(m1[1]*m2[7])+(m1[2]*m2[11])+(m1[3]*m2[15]);
        m3[3]=e3;
    
    e3=(m1[4]*m2[0])+(m1[5]*m2[4])+(m1[6]*m2[8])+(m1[7]*m2[12]);
        m3[4]=e3;
    
    e3=(m1[4]*m2[1])+(m1[5]*m2[5])+(m1[6]*m2[9])+(m1[7]*m2[13]);
        m3[5]=e3;

    e3=(m1[4]*m2[2])+(m1[5]*m2[6])+(m1[6]*m2[10])+(m1[7]*m2[14]);
        m3[6]=e3;

    e3=(m1[4]*m2[3])+(m1[5]*m2[7])+(m1[6]*m2[11])+(m1[7]*m2[15]);
        m3[7]=e3;

    e3=(m1[8]*m2[0])+(m1[9]*m2[4])+(m1[10]*m2[8])+(m1[11]*m2[12]);
        m3[8]=e3;

    e3=(m1[8]*m2[1])+(m1[9]*m2[5])+(m1[10]*m2[9])+(m1[11]*m2[13]);
        m3[9]=e3;

    e3=(m1[8]*m2[2])+(m1[9]*m2[6])+(m1[10]*m2[10])+(m1[11]*m2[14]);
        m3[10]=e3;

    e3=(m1[8]*m2[3])+(m1[9]*m2[7])+(m1[10]*m2[11])+(m1[11]*m2[15]);
        m3[11]=e3;

    e3=(m1[12]*m2[0])+(m1[13]*m2[4])+(m1[14]*m2[8])+(m1[15]*m2[12]);
        m3[12]=e3;

    e3=(m1[12]*m2[1])+(m1[13]*m2[5])+(m1[14]*m2[9])+(m1[15]*m2[13]);
        m3[13]=e3;

    e3=(m1[12]*m2[2])+(m1[13]*m2[6])+(m1[14]*m2[10])+(m1[15]*m2[14]);
        m3[14]=e3;

    e3=(m1[12]*m2[3])+(m1[13]*m2[7])+(m1[14]*m2[11])+(m1[15]*m2[15]);
        m3[15]=e3;
       
        for (int m=0; m<square; m++) {
        Console.WriteLine("\n"+ m3[m]);
        }
}

    }

    if (choice=="d") {
    Console.Write("Dimension: ");
    int input=Convert.ToInt32(Console.ReadLine());
    Console.WriteLine("\n");

    int square = input*input;
    float [] m1=new float[square];
    float det;

    for (int i=0; i<square; i++) {
      float e1=Convert.ToSingle(Console.ReadLine());
      m1[i]=e1;
    }
    Console.WriteLine("\n");
    
    if (input==2) {
        det=(m1[0]*m1[3])-(m1[1]*m1[2]);
        Console.WriteLine(det);
        if (det!=0) {
            Console.WriteLine("Is invertible");

            //float [] mi = new float [square];
            float a, b, c, d;

            a=(float)((1+((float)(m1[1]*m1[2])/(float)((m1[3]*m1[0])-(m1[1]*m1[2])))))/(float)m1[0];
            b=((float)(-m1[1])/(float)((m1[3]*m1[0])-(m1[2]*m1[1])));
            c=((float)(-m1[2])/(float)((m1[3]*m1[0])-(m1[2]*m1[1])));
            d=((float)(m1[0])/(float)((m1[3]*m1[0])-(m1[2]*m1[1])));
 
            Console.WriteLine("\n"+a+"\n"+b+"\n"+c+"\n"+d);


            /*for (int m=0; m<square; m++) {
             Console.WriteLine("\n"+ mi[m]);
            }*/
       }
        else {
           Console.WriteLine("Is not invertible");
        }
    }
    
    if (input==3) {
        det=((m1[0]*m1[4]*m1[8])+(m1[1]*m1[5]*m1[6])+(m1[2]*m1[3]*m1[7]))-((m1[0]*m1[5]*m1[7])+(m1[1]*m1[3]*m1[8])+(m1[2]*m1[4]*m1[6]));
        Console.WriteLine(det);
        if (det!=0) {
            Console.WriteLine("Is invertible");
        }
        else {
            Console.WriteLine("Is not invertible");
        }
    }

    if (input==4) {
        //det=((m1[0]*m1[5]*m1[10]*m1[15])+(m1[1]*m1[6]*m1[11]*m1[12])+(m1[2]*m1[7]*m1[8]*m1[13])+(m1[3]*m1[4]*m1[9]*m1[14]))-((m1[12]*m1[9]*m1[6]*m1[3])+(m1[13]*m1[10]*m1[7]*m1[0])+(m1[14]*m1[11]*m1[4]*m1[1])+(m1[15]*m1[8]*m1[5]*m1[2]));
        float det1, det2, det3, det4;
        
        float [] m2= new float [9];
        float [] m3= new float [9];
        float [] m4= new float [9];
        float [] m5= new float [9];
        
        m2.SetValue(value: m1[5], index:0);
        m2.SetValue(value: m1[6], index:1);
        m2.SetValue(value: m1[7], index:2);
        m2.SetValue(value: m1[9], index:3);
        m2.SetValue(value: m1[10], index:4);
        m2.SetValue(value: m1[11], index:5);
        m2.SetValue(value: m1[13], index:6);
        m2.SetValue(value: m1[14], index:7);
        m2.SetValue(value: m1[15], index:8);
        
        det1=m1[0]*(((m2[0]*m2[4]*m2[8])+(m2[1]*m2[5]*m2[6])+(m2[2]*m2[3]*m2[7]))-((m2[0]*m2[5]*m2[7])+(m2[1]*m2[3]*m2[8])+(m2[2]*m2[4]*m2[6])));
        
        m3.SetValue(value: m1[4], index:0);
        m3.SetValue(value: m1[6], index:1);
        m3.SetValue(value: m1[7], index:2);
        m3.SetValue(value: m1[8], index:3);
        m3.SetValue(value: m1[10], index:4);
        m3.SetValue(value: m1[11], index:5);
        m3.SetValue(value: m1[12], index:6);
        m3.SetValue(value: m1[14], index:7);
        m3.SetValue(value: m1[15], index:8);

        det2=m1[1]*(((m3[0]*m3[4]*m3[8])+(m3[1]*m3[5]*m3[6])+(m3[2]*m3[3]*m3[7]))-((m3[0]*m3[5]*m3[7])+(m3[1]*m3[3]*m3[8])+(m3[2]*m3[4]*m3[6])));

        m4.SetValue(value: m1[4], index:0);
        m4.SetValue(value: m1[5], index:1);
        m4.SetValue(value: m1[7], index:2);
        m4.SetValue(value: m1[8], index:3);
        m4.SetValue(value: m1[9], index:4);
        m4.SetValue(value: m1[11], index:5);
        m4.SetValue(value: m1[12], index:6);
        m4.SetValue(value: m1[13], index:7);
        m4.SetValue(value: m1[15], index:8);

        det3=m1[2]*(((m4[0]*m4[4]*m4[8])+(m4[1]*m4[5]*m4[6])+(m4[2]*m4[3]*m4[7]))-((m4[0]*m4[5]*m4[7])+(m4[1]*m4[3]*m4[8])+(m4[2]*m4[4]*m4[6])));
        
        m5.SetValue(value: m1[4], index:0);
        m5.SetValue(value: m1[5], index:1);
        m5.SetValue(value: m1[6], index:2);
        m5.SetValue(value: m1[8], index:3);
        m5.SetValue(value: m1[9], index:4);
        m5.SetValue(value: m1[10], index:5);
        m5.SetValue(value: m1[12], index:6);
        m5.SetValue(value: m1[13], index:7);
        m5.SetValue(value: m1[14], index:8);

        det4=m1[3]*(((m5[0]*m5[4]*m5[8])+(m5[1]*m5[5]*m5[6])+(m5[2]*m5[3]*m5[7]))-((m5[0]*m5[5]*m5[7])+(m5[1]*m5[3]*m5[8])+(m5[2]*m5[4]*m5[6])));

        det=det1-det2+det3-det4;
        
        Console.WriteLine(det);
        if (det!=0) {
            Console.WriteLine("Is invertible");
        }
        else {
            Console.WriteLine("Is not invertible");
        }
    }

    }

Console.ReadKey();
  }
  
}
