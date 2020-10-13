# Currency 
Aplikasi ini mencakup fungsi penghitungan nilai tukar mata uang dari dollar
ke rupiah.

## Scope  & Functionalities
- User dapat memasukkan angka
- User dapat menyentuh tombol hitung
- User mendapat info "INVALID"jika yang dimasukkan berupa text


## coding

 ```csharp
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

```