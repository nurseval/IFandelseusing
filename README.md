# IFandelseusing
Vize-final notlarına göre geçtin-kaldın programı
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ifelseyapısı
{
    internal class Program
    {
        static void Main(string[] args)
        {
            double vize, final,sonuc;

            Console.WriteLine("Vize Notunu Giriniz : ");

            vize = Convert.ToDouble(Console.ReadLine());

            vize = vize * 40 / 100;

            Console.WriteLine("Final Notunu Giriniz : ");

            final = Convert.ToDouble(Console.ReadLine());


            final = final * 70 / 100;
            sonuc = (final + vize);

            Console.WriteLine("Not Ortalaması :  "+ sonuc );
            

            if (sonuc < 50)
            {
                Console.WriteLine("Öğrenci Sınıfı Geçemedi! :");
            }
            else
            {
                Console.WriteLine("Tebrikler Sınıf GEÇİLDİ.");
            }
            Console.ReadKey();
        }
            
        
    }
}
[Patika Dev Sayfam](https://app.patika.dev/sevaalnuur)