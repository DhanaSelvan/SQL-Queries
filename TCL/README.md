# TCL Queries


## 1. BEGIN TRANSACTION Command

-> Starts a new transaction.<br>

<b>Syntax</b><br>
BEGIN TRANSACTION [transaction_name];<br>

## 2. COMMIT Command

-> Saves all changes made during the transaction.<br>

<b>Syntax</b><br>
COMMIT;<br>

## 3. ROLLBACK Command

-> Undoes all changes made during the transaction.<br>

<b>Syntax</b><br>
ROLLBACK;<br>

## 4. SAVEPOINT Command

-> Creates a savepoint within the current transaction.<br>

<b>Syntax</b><br>
SAVEPOINT savepoint_name;<br>