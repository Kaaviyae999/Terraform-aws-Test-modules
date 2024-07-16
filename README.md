module "db-instances" {
  source = "basil1987/db-instances"
  dbport = 3307
  typeofinstance = "t2.micro"
}
