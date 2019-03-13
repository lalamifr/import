class ContactNewsletterImportUpdate implements ToCollection, WithHeadingRow
{
    use Importable;

    private $data;


    public function __construct(array $data = [])
    {
        $this->data = $data; 
    }
	public function collection(collection $row)
    {
	// your code here
	// the array data in the controller is placed like this

	 $this->data['dateOpMail'] 	
