# login-form

import Image from "next/image";

export default function Home() {
  return (
    <section className="bg-white">
      <div className="flex flex-col items-center justify-center px-6 py-8 mx-auto md:h-screen lg:py-0">
        <a
          href="#"
          className="flex items-center mb-6 text-2xl font-semibold text-gray-900 dark:text-white"
        ></a>
        <div className="w-full shadow-inner  bg-white rounded-lg dark:border md:mt-0 sm:max-w-md xl:p-0">
          <div className="p-6 space-y-4 md:space-y-6 sm:p-8">
            <h1 className="flex text-xl font-bold leading-tight tracking-tight bg-cyan-500 rounded-2xl focus:border-primary-600  w-full p-2.5  text-white md:text-2xl justify-center">
              ログイン
            </h1>
            <form className="space-y-4 md:space-y-6" action="#">
              <div>
                <label
                  htmlFor="id"
                  className="block mb-2 text-sm font-medium text-gray-900 dark:text-white"
                >
                  あなたの　ID
                </label>
                <input
                  type="id"
                  name="id"
                  id="id"
                  className="bg-gray-50 border border-gray-300 text-black sm:text-sm rounded-lg focus:ring-primary-600 focus:border-primary-600 block w-full p-2.5 dark:bg-white   dark:border-gray-600 dark:placeholder-gray-400 dark:text-white dark:focus:ring-blue-500 dark:focus:border-blue-500"
                  placeholder="ID　入力してください"
                />
              </div>

              <button
                type="submit"
                className="w-full text-white bg-red-700 hover:bg-primary-700 focus:ring-4 focus:outline-none focus:ring-primary-300 font-extrabold rounded-lg text-sm px-5 py-2.5 text-center dark:bg-primary-600 dark:hover:bg-primary-700 dark:focus:ring-primary-800"
              >
                確定
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>
  );
}
