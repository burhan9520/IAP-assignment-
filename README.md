# IAP-assignment-
<!DOCTYPE html>
<html>
    <head></head>
        <body>
           <form method="save" action="save php">
            <label >PATIENTS NAME</label>
            <input placeholder="enter name" name="frame" type="text"/>
            <br>
            <table style="border:1px solid rgb(216, 219, 217);">
                <tr>
            <td><Label>BIO</label></td>
            </tr>
            <tr>
            <td><label>GENDER</label></td>
            <td><input type="radio"name="gender"/>male</td>
           <td><input type="radio"name="gender"/>female</td>
           <td><input type="radio"name="gender"/>others</td>
            </tr>
            <tr><td><label>AGE</label></td>
            <td><input type="radio"name="age"/>0-12  YRS</td>
           <td><input type="radio"name="age"/>13-19 YRS</td>
            <td><input type="radio"name="age"/>20-35 YRS</td>
            <td><input type="radio" name="age"/> >35 YRS</td>
            </tr>
            </tr>
            </table>
            <br>
            <table style="border:1px solid rgb(216, 219, 217);">
                <tr>
            <td><label>BlOOD PRESSURE</label></td>
            </tr>
            <br>
            <td><label>Systolic(mmHg)</label></td>
            <td><input type=""placeholder="" name=""/></td>
            
            <td><label>Diastolic(mmHg)</label></td>
            <td><input type=""placeholder="" name=""/></td>
            
            </table>
            <br>
            <table style="border:1px solid rgb(216, 219, 217);">
                <tr>
            <td><label>BODY MASS INDEX</label></td>
            </tr>
            <br>
            <td><label>Weight(kgs)</label></td>
            <td><input type="" placeholder="" name=""/></td>

            <td><label>Height(metres)</label></td>
           <td><input type="" placeholder="" name=""/></td>
            </table>
            <br>
            <tr>
                <table style="border:1px solid rgb(216, 219, 217);">
            <tr>
            <td><Label>STATUS</Label></td>
            </tr>
            <td><input type="button" name="Generate" value="Generate"/></td>
            <label></label>
           <td><input type="button" name="cancel" value="cancel"/></td>
        </tr>
                </table>
            <br>
            <textarea name="comments" rows="8" cols="80">
            </textarea>
            </form>
            </body>
