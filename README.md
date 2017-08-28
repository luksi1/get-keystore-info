# get-keystore-info

Return information from a Java Keystore via bash in JSON format

## Description

Retrieve infromation from a Java keystore in JSON format. Returns the following information:

- keystore file
- alias
- days_remaining
- issuer
- owner

## Usage

./get-keystore-info --keystore <KEYSTORE> --password <PASSWORD>

## Notes

The original script can be found here: http://www.davidgouveia.net/2013/07/simple-script-to-check-expiry-dates-on-a-java-keystore-jks-file/ and has been modified to remove the threshold and output a JSON file instead.
