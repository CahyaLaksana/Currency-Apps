# Currency Apps
aplikasi ini mencakup fungsi perhitungan nilai tukar mata uang dari dollar ke
rupiah.

## Coding

'''csharp

namespace CurrencyApps

{
    
    public partial class MainWindow : Window
    {
        public MainWindow()
        {
            InitializeComponent();
        }

        private void Button_Hitung_Click(object sender, RoutedEventArgs e)
        {
            var nominalString = InputTextBox.Text;
            resultLabel.Content = nominalString;   
        }
    }
}

''' 
