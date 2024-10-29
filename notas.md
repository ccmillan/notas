## crear archivo

mkdir 'file_name'
code .(abre el documento en vscode)

## crear reac -vite file

cd Desktop
npm create vite@latest "file name"

follow- run instructions shown by terminal
cd "file"
npm i
npm run dev

## eliminar archivos

App.css

on App.jsx - eliminar todos los import y la informacion dentro del return stament

## Create a new repository on the command line

touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:alexpchin/<reponame>.git
git push -u origin master

## Clonar

git clone (url del repo)

## Clonar y actualizar repo de Github

git init
git add .
git commit -m "nombre del commit"

## Push an existing repository from the command line

git remote add origin git@github.com:alexpchin/<reponame>.git
git push -u origin master

## Pushing commitments

hacer la actualizacion

git add .
git commit -m "comentario"
git push

## actualizar repo

git pull

## forms

npm install react-hook-form

const { register, handleSubmit } = useForm();

const enviar = (data) => {
console.log(data);
<input
type="mail"
placeholder="Igresa tu e-mail"
{...register("email")}
/>
}
