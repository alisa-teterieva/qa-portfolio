<table>
  <thead>
    <tr>
      <th>ID</th>
      <th>Feature</th>
      <th>Description</th>
      <th>Preconditions</th>
      <th>Test data</th>
      <th>Steps</th>
      <th>Expected result</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TC-001</td>
      <td>Registration form</td>
      <td>Verify successful registration with valid data</td>
      <td>Registration form is opened<br>No existing user with Email Test001@gmail.com</td>
      <td>Email: Test001@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms & Conditions<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-002</td>
      <td>Registration form</td>
      <td>Verify successful registration with all allowed Email characters</td>
      <td>Registration form is opened<br>No existing user with Email Te.st_002@Test-domain.123.com</td>
      <td>Email: Te.st_002@Test-domain.123.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms & Conditions<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-003</td>
      <td>Registration form</td>
      <td>Verify successful registration with all allowed Password characters</td>
      <td>Registration form is opened<br>No existing user with Email Test003@gmail.com</td>
      <td>Email: Test003@gmail.com<br>Password: Test_Pass@777!<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms & Conditions<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-004</td>
      <td>Registration form</td>
      <td>Verify successful registration with all allowed Company characters</td>
      <td>Registration form is opened<br>No existing user with Email Test004@gmail.com</td>
      <td>Email: Test004@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: Test-Company004</td>
      <td>1. Fill in all fields<br>2. Check Terms & Conditions<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-005</td>
      <td>Registration form / Terms & Conditions</td>
      <td>Verify registration attempt with unchecked Terms & Conditions checkbox</td>
      <td>Registration form is opened<br>No existing user with Email Test005@gmail.com</td>
      <td>Email: Test005@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Click Register (without checking Terms)</td>
      <td>Registration is not completed<br>validation error for unchecked Terms & Conditions</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-006</td>
      <td>Registration form / Country</td>
      <td>Verify registration attempt with Country not explicitly selected</td>
      <td>Registration form is opened<br>No existing user with Email Test006@gmail.com</td>
      <td>Email: Test006@gmail.com<br>Password: testpassword<br>Country: (not selected)<br>Company: company</td>
      <td>1. Fill in Email, Password, Company<br>2. Leave Country as is<br>3. Check Terms<br>4. Click Register</td>
      <td>Registration is not completed<br>validation error for Country field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-007</td>
      <td>Registration form / Email</td>
      <td>Verify registration attempt when entering an already registered Email</td>
      <td>Registration form is opened<br>User with Email Test007@gmail.com already exists</td>
      <td>Email: Test007@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error "Email is already registered"</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-008</td>
      <td>Registration form / Email</td>
      <td>Verify registration attempt with empty Email field</td>
      <td>Registration form is opened</td>
      <td>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in Password, Country, Company<br>2. Leave Email empty<br>3. Check Terms<br>4. Click Register</td>
      <td>Registration is not completed<br>validation error "Email cannot be empty"</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-009</td>
      <td>Registration form / Email</td>
      <td>Verify registration with empty Email local part</td>
      <td>Registration form is opened</td>
      <td>Email: @gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-010</td>
      <td>Registration form / Email</td>
      <td>Verify registration with minimum Email local part length</td>
      <td>Registration form is opened<br>No existing user with Email 1@gmail.com</td>
      <td>Email: 1@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-011</td>
      <td>Registration form / Email</td>
      <td>Verify registration with maximum Email local part length</td>
      <td>Registration form is opened<br>No existing user with Email aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa@gmail.com</td>
      <td>Email: aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-012</td>
      <td>Registration form / Email</td>
      <td>Verify registration with Email local part exceeding maximum length</td>
      <td>Registration form is opened</td>
      <td>Email: aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa1@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-013</td>
      <td>Registration form / Email</td>
      <td>Verify registration with dot in invalid position in Email local part</td>
      <td>Registration form is opened</td>
      <td>Email: .Test013@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-014</td>
      <td>Registration form / Email</td>
      <td>Verify registration with quoted Email local part containing consecutive dots</td>
      <td>Registration form is opened<br>No existing user with Email Test..014@gmail.com</td>
      <td>Email: Test..014@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-015</td>
      <td>Registration form / Email</td>
      <td>Verify registration without @ symbol in Email</td>
      <td>Registration form is opened</td>
      <td>Email: Test015gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-016</td>
      <td>Registration form / Email</td>
      <td>Verify registration with hyphen in invalid position in Email domain</td>
      <td>Registration form is opened</td>
      <td>Email: Test016@-gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-017</td>
      <td>Registration form / Email</td>
      <td>Verify registration with empty Email domain part</td>
      <td>Registration form is opened</td>
      <td>Email: Test017@<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-018</td>
      <td>Registration form / Email</td>
      <td>Verify registration with minimum Email domain length</td>
      <td>Registration form is opened<br>No existing user with Email Test018@a.b</td>
      <td>Email: Test018@a.b<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-019</td>
      <td>Registration form / Email</td>
      <td>Verify registration with maximum Email domain length</td>
      <td>Registration form is opened<br>No existing user with Email Test019@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.a</td>
      <td>Email: Test019@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.a<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-020</td>
      <td>Registration form / Email</td>
      <td>Verify registration with Email domain exceeding maximum length</td>
      <td>Registration form is opened</td>
      <td>Email: Test020@aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa.aa<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-021</td>
      <td>Registration form / Email</td>
      <td>Verify registration with dot in invalid position in Email domain</td>
      <td>Registration form is opened</td>
      <td>Email: Test021@gmailcom.<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-022</td>
      <td>Registration form / Email</td>
      <td>Verify registration with Email containing non-Latin characters</td>
      <td>Registration form is opened</td>
      <td>Email: Тест022@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-023</td>
      <td>Registration form / Email</td>
      <td>Verify registration with Email containing multiple @ symbols</td>
      <td>Registration form is opened</td>
      <td>Email: Test023@gmail@mail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-024</td>
      <td>Registration form / Email</td>
      <td>Verify registration with Email containing spaces</td>
      <td>Registration form is opened</td>
      <td>Email: Test 024@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Email field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-025</td>
      <td>Registration form / Password</td>
      <td>Verify registration with empty Password</td>
      <td>Registration form is opened<br>No existing user with Email Test025@gmail.com</td>
      <td>Email: Test025@gmail.com<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in Email, Country, Company<br>2. Leave Password empty<br>3. Check Terms<br>4. Click Register</td>
      <td>Registration is not completed<br>validation error for Password field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-026</td>
      <td>Registration form / Password</td>
      <td>Verify registration with Password containing non-Latin characters</td>
      <td>Registration form is opened<br>No existing user with Email Test026@gmail.com</td>
      <td>Email: Test026@gmail.com<br>Password: тестпароль<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Password field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-027</td>
      <td>Registration form / Password</td>
      <td>Verify registration with Password of minimum length</td>
      <td>Registration form is opened<br>No existing user with Email Test027@gmail.com</td>
      <td>Email: Test027@gmail.com<br>Password: 12345678<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-028</td>
      <td>Registration form / Password</td>
      <td>Verify registration with Password of maximum length</td>
      <td>Registration form is opened<br>No existing user with Email Test028@gmail.com</td>
      <td>Email: Test028@gmail.com<br>Password: 1234567812345678<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-029</td>
      <td>Registration form / Password</td>
      <td>Verify registration with Password exceeding maximum length</td>
      <td>Registration form is opened<br>No existing user with Email Test029@gmail.com</td>
      <td>Email: Test029@gmail.com<br>Password: 1234567812345678gbh<br>Country: Ukraine<br>Company: company</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Password field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-030</td>
      <td>Registration form / Company</td>
      <td>Verify registration with empty Company field</td>
      <td>Registration form is opened<br>No existing user with Email Test030@gmail.com</td>
      <td>Email: Test030@gmail.com<br>Password: testpassword<br>Country: Ukraine</td>
      <td>1. Fill in Email, Password, Country<br>2. Leave Company empty<br>3. Check Terms<br>4. Click Register</td>
      <td>Registration is not completed<br>validation error for Company field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-031</td>
      <td>Registration form / Company</td>
      <td>Verify registration with Company name of minimum length</td>
      <td>Registration form is opened<br>No existing user with Email Test031@gmail.com</td>
      <td>Email: Test031@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: abc</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-032</td>
      <td>Registration form / Company</td>
      <td>Verify registration with Company name of maximum length</td>
      <td>Registration form is opened<br>No existing user with Email Test032@gmail.com</td>
      <td>Email: Test032@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>User is successfully registered<br>no validation errors</td>
      <td>Delete the user after test</td>
    </tr>
    <tr>
      <td>TC-033</td>
      <td>Registration form / Company</td>
      <td>Verify registration with Company name exceeding maximum length</td>
      <td>Registration form is opened<br>No existing user with Email Test033@gmail.com</td>
      <td>Email: Test033@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: aaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa1</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Company field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-034</td>
      <td>Registration form / Company</td>
      <td>Verify registration with Company name containing special characters</td>
      <td>Registration form is opened<br>No existing user with Email Test034@gmail.com</td>
      <td>Email: Test034@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: Company@%!</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Company field</td>
      <td></td>
    </tr>
    <tr>
      <td>TC-035</td>
      <td>Registration form / Company</td>
      <td>Verify registration with Company name containing non-Latin characters</td>
      <td>Registration form is opened<br>No existing user with Email Test035@gmail.com</td>
      <td>Email: Test035@gmail.com<br>Password: testpassword<br>Country: Ukraine<br>Company: компанія</td>
      <td>1. Fill in all fields<br>2. Check Terms<br>3. Click Register</td>
      <td>Registration is not completed<br>validation error for Company field</td>
      <td></td>
    </tr>
  </tbody>
</table>
