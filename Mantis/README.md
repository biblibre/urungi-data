# Mantis layers and dashboard

Those files have been written for BibLibre Mantis customer support platform.
There are some informations that are specific to our usage of Mantis.
 - all BibLibre accounts start with an _ Somme of our staff are dedicated to support. In the layer, the field "pôle assignataire" is based on this: if user start with a _ then he/she is from BibLibre. Members of the support team are hardcoded in the field definition
 - our project are organised with parents. For example we have a "maintenance Koha", each Koha customer project being a sub-project of this one. The "Projet pôle support" (in the folder "projet") uses this information
 - we have some local values for status, see ("statut" field in "Ticket" folder)
 - the field "hébergé ou non" (under "Projet" folder) is calculated from the project name. If it has a "(h)" then it's a customer we're hosting.


