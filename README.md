# found-value

package com.company;

import jdk.swing.interop.SwingInterOpUtils;

import java.util.Scanner;

class JAVA
{
    public static void main (String args[])
    {
        int arr[]={5,2,6,8};
        Scanner n=new Scanner(System.in);
        int num;
        num=n.nextInt();
        boolean f=false;
        for (int i = 0; i < arr.length; i++)
        {
            if(arr[i]==num)
            {
                f=true;
                break;
            }
        }
        if (f)
        {
            System.out.println("Found");
        }
        else
        {
            System.out.println("not Found");
        }
    }
}



