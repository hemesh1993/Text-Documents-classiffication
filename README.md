# 2018 ALTA 2018 challenge Description: Classification Patent Applications

Basic Task Description:
When a patent application is submitted there is a process where the application is classified by examiners of patent offices or other people. Patent classifications make it feasible to search quickly for documents about earlier disclosures similar to or related to the invention for which a patent is applied for, and to track technological trends in patent applications.

The International Patent Classification (IPC) is agreed internationally. A patent can have several classification symbols but there is one which is the primary one. This is what is called the primary IPC mark.

An IPC classification symbol is of the form A01B 1/00, where each component has a special meaning:

Section symbols from A to H as follows:

A: Human necessities

B: Performing operations, transporting

C: Chemistry, metallurgy

D: Textiles, paper

E: Fixed constructions

F: Mechanical engineering, lighting, heating, weapons, blasting

G: Physics

H: Electricity

01: Class; this is a two-digit number that represents a class within the section.

B: Subclass; this is an additional capital letter.

1/00: Group; each group symbol consists of the subclass symbol followed by two numbers separated by an oblique stroke.

For example, an application for a patent about lasers might have the following two IPC marks, where the first one is the primary IPC mark:

H01S 3/00 (Lasers)

H01S 3/14 (Lasers characterised by the material used as the active medium)

Some patent applications may refer to several sections of the IPC and this would be indicated by the presence of several IPC marks. 
For example, the following application would have a primary IPC mark about fittings for hats and an additional IPC mark for pyjamas:

A42C 5/00 (Fittings or trimmings for hats)

A41D 10/00 (Pyjamas; Nightdresses)

The data is collected from the kaggle - ALTA 2018 challange which is available from the link - https://www.kaggle.com/c/alta-2018-challenge/data.

Data contains-

File descriptions:

patents.zip - The text files with the patents

train_data.csv - the training set

test_data.csv - the test set

Data fields in train data:
id - an anonymous id unique to a given patent; the corresponding patent is a text file with the name id.txt

first_ipc_mark_section - the main section of the first IPC mark (from A to H)


The goal of this task is to automatically classify Australian patents into one of the principal International Patent Classification sections. This is the first character (A to H) of the primary IPC mark. We have downloaded nearly 5,000 documents, of which we have reserved 1,000 documents for the evaluation of the systems.


