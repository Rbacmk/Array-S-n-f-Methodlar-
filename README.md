# Array-S-n-f-Methodlar-
 //Array Sınıfı Methodları
            // Sort sıralama işlemi
           
            int[] sayiDizisi = { 23, 12, 4, 86, 72, 3, 11, 17 };
            Console.WriteLine("*****SIRASIZ LİSTE*****");
            foreach (var sayi in sayiDizisi)
            {

                Console.WriteLine(sayi);
            }
           Array.Sort(sayiDizisi);

            foreach (var sayi in sayiDizisi)
            {

                Console.WriteLine(sayi);
            }
            //CLEAR -DEĞERİ SIFIRLIYOR.
            Console.WriteLine("ARRAY CLEAR");
            // sayiDizisi elemanlarını kullanarak 2.ndexten itibareb 2 tane elemanı sıfırlar.

            Array.Clear(sayiDizisi, 2, 2);
            foreach (var sayi in sayiDizisi)
            {

                Console.WriteLine(sayi);
            }
            // reverse
            Array.Reverse(sayiDizisi);
            foreach (var sayi in sayiDizisi)
            {

                Console.WriteLine(sayi);
            }
            //IndexOf
            
            

                Console.WriteLine(Array.IndexOf(sayiDizisi,23));
            // RESİZE
            Array.Resize<int>(ref sayiDizisi, 9);
            sayiDizisi[8] = 99;
            foreach (var sayi in sayiDizisi)
            {

                Console.WriteLine(sayi);
            }





        }    
