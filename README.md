## Installation

```bash
pip install -r requirements.txt
playwright install
```

## Usage

```bash
python app.py
```

Enter one or more NIBs when prompted.

## Output Example

```json
{
    "nama_perusahaan": "Company Name",
    "skala_badan_usaha": "Usaha Mikro",
    "projects_investment": {
        "R-XXXXXXXXXXXXX": 5000000
    }
}
```

If a company has no projects:

```json
{
    "nama_perusahaan": "Company Name",
    "skala_badan_usaha": "Usaha Mikro",
    "projects_investment": {}
}
```

## Notes

* Replace the OSS login credentials before running.
* Output files are automatically saved in the `data_nib` folder.
* If the search occasionally fails, simply run the script again.

## Author

Aufatir Diaul Haq
