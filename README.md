Dwi_Febri_Riyono
================

kelasSI13F_Dwi_Febri_Riyono_13311053T_TugasInput
/*
* To change this license header, choose License Headers in Project Properties.
* To change this template file, choose Tools | Templates
* and open the template in the editor.
*/
package newpackage;
import java.util.Scanner;
/**
*
* @author Hp
*/
public class DwiRiyono {
/**
* @param args the command line arguments
*/
public static void main(String[] args) {
Scanner input=new Scanner(System.in);
String nama, npm, kelas, tgl;
System.out.print("Masukkan Nama Anda : ");
nama = input.nextLine();
System.out.print("Masukkan Npm Anda : ");
npm = input.nextLine();
System.out.print("Masukkan Kelas : ");
kelas = input.nextLine();
System.out.println("Masukan Tgl Lahir : ");
tgl = input.nextLine();
//output
System.out.println("Nama :"+nama);
System.out.println("Npm :"+npm);
System.out.println("Kelas :"+kelas);
System.out.println("Tgl Lahir :"+tgl);
}
} 