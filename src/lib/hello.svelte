<h1>inschrijven</h1>

<form>
    <fieldset>
        <legend>persoonlijke gegevens</legend>
        <label for="Voornaam">
<!--            Voornaam-->
            <input id="Voornaam"  type="text" required
                   placeholder="Voornaam"
                    />
        </label>
        <label for="Tussenvoegsel">
<!--            Tussenvoegsel-->
            <input id="Tussenvoegsel" placeholder="Tussenvoegsel"  type="text"/>
        </label>
        <label for="Achternaam">
<!--            Achternaam-->
            <input id="Achternaam"  placeholder="Achternaam"  type="text"/>
        </label>
        <label for="functie">
<!--            Functie-->
            <input id="functie" placeholder="Functie" type="text"/>
        </label>
        <label for="email">
<!--            E-mail-->
            <input id="email" placeholder="E-mail" type="email"/>
        </label>
        <label for="Mobiel">
<!--            Mobiel-->
            <input id="Mobiel" placeholder="Mobiel"  type="tel"/>
        </label>
        <label for="Bedrijfsnaam">
<!--            Bedrijfsnaam-->
            <input id="Bedrijfsnaam"  placeholder="Bedrijfsnaam"  type="text"/>
        </label>
        <label for="Bedrijfswebsite">
<!--            Bedrijfswebsite-->
            <input id="Bedrijfswebsite"  placeholder="Bedrijfswebsite"  type="text"/>
        </label>
        <label for="ik wil graag lid worden omdat">
<!--            ik wil graag lid worden omdat-->
            <input id="ik wil graag lid worden omdat"  placeholder="ik wil graag lid worden omdat"  type="text"/>
        </label>
        <label for="FTE">
            FTE
            <select id="FTE" >
                <option value="1-9">
                    1-9
                </option>
                <option value="10-24">
                    10-24
                </option>
                <option value="25-49">
                    25-49
                </option>
                <option value="50-99">
                    50-99
                </option>
                <option value="100-249">
                    100-249
                </option>
                <option value="250+">
                  250
                </option>
            </select>

        </label>


    </fieldset>
</form>

<style>
    fieldset{
        border: none;
    }
    legend{
        position: absolute;
        top: 0;
        left: -9999px;
    }
    input{

        border: none;
        margin-bottom: 0.8rem;
    }
    label {
        margin-top: 1.8rem;
        display: flex;
        flex-direction: column;
        justify-content: center;
        width: 100%;
        border-bottom: 1px solid black;
    }
</style>