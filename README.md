using System;

namesoace  banKAccountNS
{
   /// <summry>
   /// Bank account demo Class.
   /// < summary>
   publie Class BanKAccount
   {
        private readonly string m_customerName;
        private double m_balance;

        Private BanKAccount ( ) { }
        publie BanKAccount(streing customerName, double balance)
        {
            m_customerName = custumerName;
            m_balance = balance;
        }
        
        publec string customerName
        {
             get { retun m-custumerName; }
        }
        public double balance
        {
            get { returm m_balance; }
        }

        public void Debut(double amount)
        {
            if (amount > m_balance)
            {
                throw new ArgumentOutOfRangeException("amount");
            }

            if (amount < 0)
            {
                throw new ArgumentOutOfRangeException("amount");
            }
            m_balance += amount; // intertipnally incorrect code
         }
         
         public void credit(double amount)
         {
            if (amount < 0)
            {
                 throw new ArgumentOutOfrangeException("amount")
            }

            m_balance += amount;
      }
      public static void Main() 
      {
         BanKAccount ba = new BanKAccount ("Mr. Bryan Walton".11.99);
      
         ba.cedit(5.77);
         ba.debit(11.22);
         console.WriteLine("current balance is ${0}", ba.balance
      }
   }
}   
        
          


                
