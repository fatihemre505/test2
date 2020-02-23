# test2
test yazıldı
 githuptan yazıldı. üzerine eklendi.
 test yazısı yazıldı.
 
 
 
 
 
 commind yap


 using (OSGBDATAEntities db = new OSGBDATAEntities())
 
 
 
 
  using (OSGBDATAEntities db = new OSGBDATAEntities())
  
  
  
   using (OSGBDATAEntities db = new OSGBDATAEntities())
   
   
    using (OSGBDATAEntities db = new OSGBDATAEntities())


       public void AdinaGoreBul(string ad)
        {
            using (OSGBDATAEntities db = new OSGBDATAEntities())
            {

                var sonuc = from t in db.TetkikBilgileri
                            where t.Adi.Contains(ad)
                            select new
                            {
                                t.Id,
                                t.TCKN,
                                t.Adi,
                                t.Soyadi,
                                t.FirmaBilgileri.FirmaAdi,
                                t.Telefonu,
                                t.DogumTarihi,
                                t.KayitTarihi,
                                t.NOT,
                                t.AlinanTutar,
                                AC = t.AC.Value,
                                ODİO = t.ODİO.Value,
                                SFT = t.SFT.Value,
                                EKG = t.EKG.Value,
                                TETANOZ = t.TETANOZ.Value,
                                KG = t.KG.Value,
                                A_HCV = t.AHCV.Value,
                                HBEAG = t.HBeAg.Value,
                                GÖZ = t.GOZ.Value,
                                ÜRE = t.URE.Value,
                                KRATİNİN = t.KREATININ.Value,
                                AST = t.AST.Value,
                                A_HBS = t.AHBS.Value,
                                A_HIV = t.AHIV.Value,
                                HBsAG = t.HBsAg.Value,
                                GAP = t.GAP.Value,
                                EXTRA = t.EKSTRA.Value,
                                TİT = t.TIT.Value,
                                CBC = t.CBC.Value,
                                PORTÖR = t.PORTOR.Value,
                                KŞ = t.KS.Value,
                                KURŞUN = t.KURSUN.Value

                            };

                dataGridViewTetkik.DataSource = sonuc.ToList();
            }

        }



           public void AdinaGoreBul(string ad)
        {
            using (OSGBDATAEntities db = new OSGBDATAEntities())
            {

                var sonuc = from t in db.TetkikBilgileri
                            where t.Adi.Contains(ad)
                            select new
                            {
                                t.Id,
                                t.TCKN,
                                t.Adi,
                                t.Soyadi,
                                t.FirmaBilgileri.FirmaAdi,
                                t.Telefonu,
                                t.DogumTarihi,
                                t.KayitTarihi,
                                t.NOT,
                                t.AlinanTutar,
                                AC = t.AC.Value,
                                ODİO = t.ODİO.Value,
                                SFT = t.SFT.Value,
                                EKG = t.EKG.Value,
                                TETANOZ = t.TETANOZ.Value,
                                KG = t.KG.Value,
                                A_HCV = t.AHCV.Value,
                                HBEAG = t.HBeAg.Value,
                                GÖZ = t.GOZ.Value,
                                ÜRE = t.URE.Value,
                                KRATİNİN = t.KREATININ.Value,
                                AST = t.AST.Value,
                                A_HBS = t.AHBS.Value,
                                A_HIV = t.AHIV.Value,
                                HBsAG = t.HBsAg.Value,
                                GAP = t.GAP.Value,
                                EXTRA = t.EKSTRA.Value,
                                TİT = t.TIT.Value,
                                CBC = t.CBC.Value,
                                PORTÖR = t.PORTOR.Value,
                                KŞ = t.KS.Value,
                                KURŞUN = t.KURSUN.Value

                            };

                dataGridViewTetkik.DataSource = sonuc.ToList();
            }

        }
        
        
           public void AdinaGoreBul(string ad)
        {
            using (OSGBDATAEntities db = new OSGBDATAEntities())
            {

                var sonuc = from t in db.TetkikBilgileri
                            where t.Adi.Contains(ad)
                            select new
                            {
                                t.Id,
                                t.TCKN,
                                t.Adi,
                                t.Soyadi,
                                t.FirmaBilgileri.FirmaAdi,
                                t.Telefonu,
                                t.DogumTarihi,
                                t.KayitTarihi,
                                t.NOT,
                                t.AlinanTutar,
                                AC = t.AC.Value,
                                ODİO = t.ODİO.Value,
                                SFT = t.SFT.Value,
                                EKG = t.EKG.Value,
                                TETANOZ = t.TETANOZ.Value,
                                KG = t.KG.Value,
                                A_HCV = t.AHCV.Value,
                                HBEAG = t.HBeAg.Value,
                                GÖZ = t.GOZ.Value,
                                ÜRE = t.URE.Value,
                                KRATİNİN = t.KREATININ.Value,
                                AST = t.AST.Value,
                                A_HBS = t.AHBS.Value,
                                A_HIV = t.AHIV.Value,
                                HBsAG = t.HBsAg.Value,
                                GAP = t.GAP.Value,
                                EXTRA = t.EKSTRA.Value,
                                TİT = t.TIT.Value,
                                CBC = t.CBC.Value,
                                PORTÖR = t.PORTOR.Value,
                                KŞ = t.KS.Value,
                                KURŞUN = t.KURSUN.Value

                            };

                dataGridViewTetkik.DataSource = sonuc.ToList();
            }

        }
